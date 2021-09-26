# swupd

> Utilitar de gestionare a pachetelor pentru Clear Linux.
> Mai multe informații: <https://docs.01.org/clearlinux/latest/guides/clear/swupd.html>.

- Actualizați la cea mai recentă versiune:

`sudo swupd update`

- Afișează versiunea curentă și verifică dacă există una mai nouă:

`swupd check-update`

- Lista pachetelor instalate:

`swupd bundle-list`

- Localizați pachetul în care există un pachet dorit:

`swupd search -b {{package}}`

- Instalați un nou pachet:

`sudo swupd bundle-add {{bundle}}`

- Îndepărtați un pachet:

`sudo swupd bundle-remove {{bundle}}`

- Corectați fișierele rupte sau lipsă:

`sudo swupd verify`
