# dbus-daemon

> Daemonul de mesaje D-Bus, care permite mai multor programe să facă schimb de mesaje.
> Mai multe informații: <https://www.freedesktop.org/wiki/Software/dbus/>.

- Rulați demonul cu un fișier de configurare:

`dbus-daemon --config-file {{path/to/file}}`

- Rulați demonul cu configurația standard a magistralei de mesaje pentru fiecare sesiune de logare:

`dbus-daemon --session`

- Rulați demonul cu configurația standard a magistralei de mesaje la nivelul întregului sistem:

`dbus-daemon --system`

- Setați adresa de ascultare și suprascrieți valoarea de configurare pentru aceasta:

`dbus-daemon --address {{address}}`

- Emite ID-ul procesului în stdout:

`dbus-daemon --print-pid`

- Forțează magistrala de mesaje să scrie în jurnalul sistemului pentru mesaje:

`dbus-daemon --syslog`
