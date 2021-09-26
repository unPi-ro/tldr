# firejail

> Procese sandbox securizate în containere folosind capacitățile Linux încorporate.
> Mai multe informații: <https://manned.org/firejail>.

- Integrați firejail cu mediul dvs. de lucru:

`sudo firecfg`

- Deschideți un Mozilla Firefox restricționat:

`firejail {{firefox}}`

- Porniți un server Apache restricționat pe o interfață și o adresă cunoscute:

`firejail --net={{eth0}} --ip={{192.168.1.244}} {{/etc/init.d/apache2}} {{start}}`

- Lista cutiilor de nisip care rulează:

`firejail --list`

- Listează activitatea de rețea din sandbox-urile în curs de execuție:

`firejail --netstats`

- Opriți un sandbox în curs de execuție:

`firejail --shutdown={{7777}}`
