# mkfs.cramfs

> Creează un sistem de fișiere ROM în interiorul unei partiții.
> Mai multe informații: <https://manned.org/mkfs.cramfs>.

- Creați un sistem de fișiere ROM în interiorul partiției 1 de pe dispozitivul b (`sdb1`):

`mkfs.cramfs {{/dev/sdb1}}`

- Creați un sistem de fișiere ROM cu un nume de volum:

`mkfs.cramfs -n {{volume_name}} {{/dev/sdb1}}`
