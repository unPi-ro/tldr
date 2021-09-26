# mimetype

> Determinați automat tipul MIME al unui fișier.
> Mai multe informații: <https://manned.org/mimetype>.

- Imprimă tipul MIME al unui fișier dat:

`mimetype {{path/to/file}}`

- Afișează numai tipul MIME, nu și numele fișierului:

`mimetype --brief {{path/to/file}}`

- Afișează o descriere a tipului MIME:

`mimetype --describe {{path/to/file}}`

- Determină tipul MIME al stdin (nu verifică un nume de fișier):

`{{some_command}} | mimetype --stdin`

- Afișează informații de depanare despre modul în care a fost determinat tipul MIME:

`mimetype --debug {{path/to/file}}`

- Afișează toate tipurile MIME posibile ale unui fișier dat, în ordine de încredere:

`mimetype --all {{path/to/file}}`

- Specificați în mod explicit codul lingvistic de 2 litere al rezultatului:

`mimetype --language {{path/to/file}}`
