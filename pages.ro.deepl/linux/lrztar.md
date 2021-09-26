# lrztar

> Un wrapper pentru `lrzip` pentru a simplifica comprimarea directoarelor.
> A se vedea deci: `tar`, `lrzuntar`, `lrunzip`.
> Mai multe informații: <https://manned.org/lrztar>.

- Arhivează un director cu `tar`, apoi comprimă:

`lrztar {{path/to/directory}}`

- La fel ca mai sus, cu ZPAQ - compresie extremă, dar foarte lentă:

`lrztar -z {{path/to/directory}}`

- Specificați fișierul de ieșire:

`lrztar -o {{path/to/file}} {{path/to/directory}}`

- Suprascrieți numărul de fire de procesare care trebuie utilizate:

`lrztar -p {{8}} {{path/to/directory}}`

- Forțați suprascrierea fișierelor existente:

`lrztar -f {{path/to/directory}}`
