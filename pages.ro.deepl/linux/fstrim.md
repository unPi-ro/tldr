# fstrim

> Eliminați blocurile nefolosite pe un sistem de fișiere montat.
> Este acceptat numai de dispozitivele de memorie flash, cum ar fi SSD și cardurile microSD.
> Mai multe informații: <https://manned.org/fstrim>.

- Tăiați blocurile nefolosite pe toate partițiile montate care o acceptă:

`sudo fstrim --all`

- Tăiați blocurile nefolosite de pe o partiție specificată:

`sudo fstrim {{/}}`

- Afișarea statisticilor după tăiere:

`sudo fstrim --verbose {{/}}`
