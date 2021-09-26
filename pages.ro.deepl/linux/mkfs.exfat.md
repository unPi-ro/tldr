# mkfs.exfat

> Creează un sistem de fișiere exfat în interiorul unei partiții.
> Mai multe informații: <https://manned.org/mkfs.exfat>.

- Creați un sistem de fișiere exfat în interiorul partiției 1 de pe dispozitivul b (`sdb1`):

`mkfs.exfat {{/dev/sdb1}}`

- Creați un sistem de fișiere cu un nume de volum:

`mkfs.exfat -n {{volume_name}} {{/dev/sdb1}}`

- Creați un sistem de fișiere cu un volum-id:

`mkfs.exfat -i {{volume_id}} {{/dev/sdb1}}`
