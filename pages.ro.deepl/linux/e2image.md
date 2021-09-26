# e2image

> Salvați metadatele critice ale sistemului de fișiere ext2/ext3/ext4 într-un fișier.
> Mai multe informații: <https://manned.org/e2image>.

- Scrie metadatele localizate pe dispozitiv într-un anumit fișier:

`e2image {{/dev/sdXN}} {{path/to/image_file}}`

- Tipărește metadatele localizate pe dispozitiv pe stdout:

`e2image {{/dev/sdXN}} -`

- Restaurați metadatele sistemului de fișiere înapoi pe dispozitiv:

`e2image -I {{/dev/sdXN}} {{path/to/image_file}}`

- Creați un fișier mare de tip "raw sparse" cu metadate la distanțele corespunzătoare:

`e2image -r {{/dev/sdXN}} {{path/to/image_file}}`

- Creați un fișier imagine QCOW2 în loc de un fișier imagine normal sau brut:

`e2image -Q {{/dev/sdXN}} {{path/to/image_file}}`
