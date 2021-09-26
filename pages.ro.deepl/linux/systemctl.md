# systemctl

> Controlați managerul de sistem și de servicii systemd.
> Mai multe informații: <https://www.freedesktop.org/software/systemd/man/systemctl.html>.

- Lista unităților eșuate:

`systemctl --failed`

- Porniți/opriți/reporniți/reîncărcați un serviciu:

`systemctl {{start|stop|restart|reload}} {{unit}}`

- Afișează starea unei unități:

`systemctl status {{unit}}`

- Activați/dezactivați o unitate pentru a fi pornită la pornire:

`systemctl {{enable|disable}} {{unit}}`

- Maschează/dezimulează o unitate pentru a preveni activarea și activarea manuală:

`systemctl {{mask|unmask}} {{unit}}`

- Reîncărcați systemd, scanând pentru unități noi sau modificate:

`systemctl daemon-reload`

- Verificați dacă o unitate este activă:

`systemctl is-active {{unit}}`

- Verificați dacă o unitate este activată:

`systemctl is-enabled {{unit}}`
