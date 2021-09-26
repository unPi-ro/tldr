# service

> Gestionați serviciile prin rularea scripturilor de init.
> Calea completă a scriptului ar trebui omisă (se presupune `/etc/init.d/`).

- Enumerați numele și starea tuturor serviciilor:

`service --status-all`

- Serviciu de pornire/oprire/repornire/reîncărcare (pornirea/oprirea ar trebui să fie întotdeauna disponibilă):

`service {{service_name}} {{start|stop|restart|reload}}`

- Efectuați o repornire completă (rulează scriptul de două ori cu start și stop):

`service {{service_name}} --full-restart`

- Afișează starea actuală a unui serviciu:

`service {{service_name}} status`
