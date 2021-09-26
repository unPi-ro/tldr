# e2freefrag

> Imprimă informațiile despre fragmentarea spațiului liber pentru sistemele de fișiere ext2/ext3/ext4.
> Mai multe informații: <https://manned.org/e2freefrag>.

- Verificați câte blocuri libere sunt prezente ca spațiu liber contiguu și aliniat:

`e2freefrag {{/dev/sdXN}}`

- Specificați dimensiunea bucăților în kiloocteți pentru a imprima câte bucățile libere sunt disponibile:

`e2freefrag -c {{chunk_size_in_kb}} {{/dev/sdXN}}`
