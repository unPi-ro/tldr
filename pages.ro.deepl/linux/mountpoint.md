# mountpoint

> Testați dacă un director este un punct de montare a unui sistem de fișiere.
> Mai multe informații: <https://manned.org/mountpoint>.

- Verifică dacă un director este un punct de montare:

`mountpoint {{path/to/directory}}`

- Verifică dacă un director este un punct de montare fără a afișa niciun rezultat:

`mountpoint -q {{path/to/directory}}`

- Afișează numerele major/minor ale sistemului de fișiere al unui punct de montare:

`mountpoint --fs-devno {{path/to/directory}}`
