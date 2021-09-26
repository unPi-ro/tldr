# whatis

> Afișați descrierile pe o linie din paginile de manual.

- Afișează o descriere dintr-o pagină de manual:

`whatis {{command}}`

- Nu întrerupeți descrierea la sfârșitul rândului:

`whatis --long {{command}}`

- Afișează descrierile pentru toate comenzile care corespund unui glob:

`whatis --wildcard {{net*}}`

- Căutați descrierile paginilor de manual cu o expresie regulată:

`whatis --regex '{{wish[0-9]\.[0-9]}}'`
