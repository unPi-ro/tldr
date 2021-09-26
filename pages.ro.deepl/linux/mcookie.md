# mcookie

> Generează numere hexazecimale aleatoare pe 128 de biți.
> Mai multe informații: <https://manned.org/mcookie>.

- Generați un număr aleatoriu:

`mcookie`

- Generează un număr aleatoriu, utilizând conținutul unui fișier ca sămânță pentru aleator:

`mcookie --file {{path/to/file}}`

- Generează un număr aleatoriu, utilizând un anumit număr de octeți dintr-un fișier ca sămânță pentru aleator:

`mcookie --file {{path/to/file}} --max-size {{number_of_bytes}}`

- Tipărește detaliile aleatoriei utilizate, cum ar fi originea și sămânța pentru fiecare sursă:

`mcookie --verbose`
