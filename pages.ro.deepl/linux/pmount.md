# pmount

> Montați dispozitive hotpluggable arbitrare ca un utilizator normal.
> Mai multe informații: <https://manned.org/pmount>.

- Montați un dispozitiv sub `/media/` (folosind dispozitivul ca punct de montare):

`pmount {{/dev/to/block/device}}`

- Montează un dispozitiv cu un tip specific de sistem de fișiere în `/media/label`:

`pmount --type {{filesystem}} {{/dev/to/block/device}} {{label}}`

- Montați un CD-ROM (sistem de fișiere de tip ISO9660) în modul doar pentru citire:

`pmount --type {{iso9660}} --read-only {{/dev/cdrom}}`

- Montați un disc formatat NTFS, forțând accesul de citire-scriere:

`pmount --type {{ntfs}} --read-write {{/dev/sdX}}`

- Afișează toate dispozitivele detașabile montate:

`pmount`
