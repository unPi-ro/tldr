# mkfs.vfat

> Creează un sistem de fișiere MS-DOS în interiorul unei partiții.
> Mai multe informații: <https://manned.org/mkfs.vfat>.

- Creați un sistem de fișiere vfat în interiorul partiției 1 de pe dispozitivul b (`sdb1`):

`mkfs.vfat {{/dev/sdb1}}`

- Creați un sistem de fișiere cu un nume de volum:

`mkfs.vfat -n {{volume_name}} {{/dev/sdb1}}`

- Creați un sistem de fișiere cu un volum-id:

`mkfs.vfat -i {{volume_id}} {{/dev/sdb1}}`

- Utilizați 5 în loc de 2 tabele de alocare a fișierelor:

`mkfs.vfat -f 5 {{/dev/sdb1}}`
