# udevadm

> Linux `udev` instrument de gestionare a Linux `udev`.
> Mai multe informații: <https://www.freedesktop.org/software/systemd/man/udevadm>.

- Monitorizați toate evenimentele dispozitivului:

`sudo udevadm monitor`

- Tipărește `uevents` trimise de kernel:

`sudo udevadm monitor --kernel`

- Tipărește evenimentele de dispozitiv după ce au fost procesate de `udev`:

`sudo udevadm monitor --udev`

- Enumeră atributele unui dispozitiv:

`sudo udevadm info --attribute-walk --path {{/dev/sda1}}`

- Reîncarcă toate regulile `udev`:

`sudo udevadm control --reload-rules`

- Declanșează toate regulile `udev` pentru a rula:

`sudo udevadm trigger`
