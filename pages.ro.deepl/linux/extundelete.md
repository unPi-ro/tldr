# extundelete

> Recuperează fișierele șterse de pe partiții ext3 sau ext4 prin analiza jurnalului.
> Vedeți și `date` pentru informații despre ora Unix și `umount` pentru demontarea partițiilor.
> Mai multe informații: <http://extundelete.sourceforge.net>.

- Restaurați toate fișierele șterse din partiția N de pe dispozitivul X:

`sudo extundelete {{/dev/sdXN}} --restore-all`

- Restaurați un fișier dintr-o cale relativă la root (nu începeți calea cu `/`):

`extundelete {{/dev/sdXN}} --restore-file {{path/to/file}}`

- Restaurați un director dintr-o cale relativă la root (nu începeți calea cu `/`):

`extundelete {{/dev/sdXN}} --restore-directory {{path/to/directory}}`

- Restaurați toate fișierele șterse după 1 ianuarie 2020 (în timpul Unix):

`extundelete {{/dev/sdXN}} --restore-all --after {{1577840400}}`
