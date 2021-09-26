# fdisk

> Un program pentru gestionarea tabelelor de partiții și a partițiilor de pe un hard disk.
> Vezi și: `partprobe`.
> Mai multe informații: <https://manned.org/fdisk>.

- Listează partițiile:

`sudo fdisk -l`

- Porniți manipulatorul de partiții:

`sudo fdisk {{/dev/sdX}}`

- După ce ați partiționat un disc, creați o partiție:

`n`

- După ce ați partiționat un disc, selectați o partiție pentru a o șterge:

`d`

- După ce ați partiționat un disc, vizualizați tabelul de partiții:

`p`

- După ce ați partiționat un disc, scrieți modificările efectuate:

`w`

- După ce ați partiționat un disc, renunțați la modificările efectuate:

`q`

- După ce ați partiționat un disc, deschideți un meniu de ajutor:

`m`
