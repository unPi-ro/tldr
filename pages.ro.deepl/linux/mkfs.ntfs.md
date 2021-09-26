# mkfs.ntfs

> Creează un sistem de fișiere NTFS în interiorul unei partiții.
> Mai multe informații: <https://manned.org/mkfs.ntfs>.

- Creați un sistem de fișiere NTFS în interiorul partiției 1 de pe dispozitivul b (`sdb1`):

`mkfs.ntfs {{/dev/sdb1}}`

- Creați un sistem de fișiere cu o etichetă de volum:

`mkfs.ntfs -L {{volume_label}} {{/dev/sdb1}}`

- Creați un sistem de fișiere cu un UUID specific:

`mkfs.ntfs -U {{UUID}} {{/dev/sdb1}}`
