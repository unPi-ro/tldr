# timedatectl

> Controlați ora și data sistemului.
> Mai multe informații: <https://manned.org/timedatectl.1>.

- Verificați ora curentă a ceasului sistemului:

`timedatectl`

- Setați direct ora locală a ceasului de sistem:

`timedatectl set-time "{{yyyy-MM-dd hh:mm:ss}}"`

- Lista fusurilor orare disponibile:

`timedatectl list-timezones`

- Setați fusul orar al sistemului:

`timedatectl set-timezone {{timezone}}`

- Activați sincronizarea prin protocolul NTP (Network Time Protocol):

`timedatectl set-ntp on`
