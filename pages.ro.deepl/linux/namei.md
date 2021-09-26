# namei

> Urmărește o cale de acces (care poate fi o legătură simbolică) până când se găsește un punct terminal (un fișier/directoriu/dispozitiv de caractere etc.).
> Acest program este util pentru a găsi probleme legate de "prea multe niveluri de legături simbolice".

- Rezolvă numele căilor de acces specificate ca parametri de argument:

`namei {{path/to/a}} {{path/to/b}} {{path/to/c}}`

- Afișați rezultatele într-un format de listă lungă:

`namei --long {{path/to/a}} {{path/to/b}} {{path/to/c}}`

- Afișează biții de mod pentru fiecare tip de fișier în stilul `ls`:

`namei --modes {{path/to/a}} {{path/to/b}} {{path/to/c}}`

- Afișează numele proprietarului și al grupului pentru fiecare fișier:

`namei --owners {{path/to/a}} {{path/to/b}} {{path/to/c}}`

- Nu urmați linkurile simbolice în timpul rezolvării:

`namei --nosymlinks {{path/to/a}} {{path/to/b}} {{path/to/c}}`
