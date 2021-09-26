# debootstrap

> Creați un sistem Debian de bază.
> Mai multe informații: <https://wiki.debian.org/Debootstrap>.

- Creați un sistem de versiuni stabile Debian în directorul `debian-root`:

`sudo debootstrap stable {{path/to/debian-root/}} http://deb.debian.org/debian`

- Creați un sistem Ubuntu 20.04 în interiorul directorului `focal-root` cu o oglindă locală:

`sudo debootstrap focal {{path/to/focal-root/}} {{file:///path/to/mirror/}}`

- Treceți la un sistem de tip bootstrap:

`sudo chroot {{path/to/root}}`

- Enumerați versiunile disponibile:

`ls /usr/share/debootstrap/scripts/`
