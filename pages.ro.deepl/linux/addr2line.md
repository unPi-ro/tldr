# addr2line

> Conversia adreselor unui fișier binar în nume de fișiere și numere de linii.
> Mai multe informații: <https://manned.org/addr2line>.

- Afișarea numelui de fișier și a numărului de linie a codului sursă de la o adresă de instrucțiune a unui executabil:

`addr2line --exe={{path/to/executable}} {{address}}`

- Afișează numele funcției, numele fișierului și numărul liniei:

`addr2line --exe={{path/to/executable}} --functions {{address}}`

- Demultiplică numele funcției pentru codul C:

`addr2line --exe={{path/to/executable}} --functions --demangle {{address}}`
