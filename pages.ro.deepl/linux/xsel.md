# xsel

> X11 instrument de selecție și manipulare a clipboard-ului.

- Utilizează ieșirea unei comenzi ca intrare a clip[b]oard-ului (echivalent cu `Ctrl C`):

`echo 123 | xsel -ib`

- Utilizați conținutul unui fișier ca intrare a clipboard-ului:

`cat {{file}} | xsel -ib`

- Afișează conținutul clipboard-ului în terminal (echivalent cu `Ctrl V`):

`xsel -ob`

- Trimite conținutul clipboard-ului într-un fișier:

`xsel -ob > {{file}}`

- Ștergeți clipboard-ul:

`xsel -cb`

- Trimite conținutul selecției primare X11 în terminal (echivalent cu un clic pe mijlocul mouse-ului):

`xsel -op`
