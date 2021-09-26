# ncdu

> Analizator de utilizare a discului cu o interfață ncurses.

- Analizează directorul de lucru curent:

`ncdu`

- Analizați un anumit director:

`ncdu {{path/to/directory}}`

- Salvați rezultatele într-un fișier:

`ncdu -o {{path/to/file}}`

- Exclude fișierele care se potrivesc cu un model, argumentul poate fi dat de mai multe ori pentru a adăuga mai multe modele:

`ncdu --exclude '{{*.txt}}'`
