# readpe

> Afișează informații despre fișierele PE.
> Mai multe informații: <https://manned.org/readpe>.

- Afișează toate informațiile despre un fișier PE:

`readpe {{path/to/executable}}`

- Afișează toate anteturile prezente într-un fișier PE:

`readpe --all-headers {{path/to/executable}}`

- Afișează toate secțiunile prezente într-un fișier PE:

`readpe --all-sections {{path/to/executable}}`

- Afișează un anumit antet dintr-un fișier PE:

`readpe --header {{dos|coff|optional}} {{path/to/executable}}`

- Enumeră toate funcțiile importate:

`readpe --imports {{path/to/executable}}`

- Lista tuturor funcțiilor exportate:

`readpe --exports {{path/to/executable}}`
