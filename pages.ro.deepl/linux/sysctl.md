# sysctl

> Listați și modificați variabilele de execuție ale kernelului.

- Afișează toate variabilele disponibile și valorile acestora:

`sysctl -a`

- Setați o variabilă de stare a kernelului care poate fi modificată:

`sysctl -w {{section.tunable}}={{value}}`

- Obține gestionarii de fișiere deschise în prezent:

`sysctl fs.file-nr`

- Obțineți limita pentru fișierele deschise simultan:

`sysctl fs.file-max`

- Aplicați modificările din `/etc/sysctl.conf`:

`sysctl -p`
