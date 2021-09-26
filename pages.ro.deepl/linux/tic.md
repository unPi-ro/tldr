# tic

> Compilați terminfo și instalați pentru ncurses.
> Mai multe informații: <https://pubs.opengroup.org/onlinepubs/007908799/xcurses/terminfo.html>.

- Compilați și instalați terminfo pentru un terminal:

`tic -xe {{terminal}} {{path/to/terminal.info}}`

- Verificați dacă există erori în fișierul terminfo:

`tic -c {{path/to/terminal.info}}`

- Imprimă locațiile bazei de date:

`tic -D`
