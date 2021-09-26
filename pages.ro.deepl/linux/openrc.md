# openrc

> Managerul de servicii OpenRC.
> Vezi și `rc-status`, `rc-update` și `rc-service`.
> Mai multe informații: <https://wiki.gentoo.org/wiki/OpenRC>.

- Treceți la un anumit nivel de execuție:

`sudo openrc {{runlevel_name}}`

- Treceți la un anumit nivel de execuție, dar nu opriți niciun serviciu existent:

`sudo openrc --no-stop {{runlevel_name}}`
