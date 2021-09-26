# e2undo

> Refaceți jurnalele de anulare pentru un sistem de fișiere ext2/ext3/ext4.
> Acest lucru poate fi folosit pentru a anula o operațiune eșuată de către un program e2fsprogs.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/e2undo.8.html>.

- Afișează informații despre un anumit fișier de anulare:

`e2undo -h {{path/to/undo_file}} {{/dev/sdXN}}`

- Efectuați o execuție de probă și afișați blocurile candidate pentru reluare:

`e2undo -nv {{path/to/undo_file}} {{/dev/sdXN}}`

- Efectuați o operațiune de anulare:

`e2undo {{path/to/undo_file}} {{/dev/sdXN}}`

- Efectuați o operațiune de anulare și afișați informații detaliate:

`e2undo -v {{path/to/undo_file}} {{/dev/sdXN}}`

- Scrieți conținutul vechi al blocului într-un fișier de anulare înainte de a suprascrie un bloc din sistemul de fișiere:

`e2undo -z {{path/to/file.e2undo}} {{path/to/undo_file}} {{/dev/sdXN}}`
