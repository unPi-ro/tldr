# procs

> Afișați informații despre procesele active.
> Mai multe informații: <https://github.com/dalance/procs>.

- Afișează lista tuturor proceselor, indicând PID-ul, utilizatorul, utilizarea CPU, utilizarea memoriei și comanda care le-a inițiat:

`procs`

- Afișează informații despre procese, dacă comenzile care le-au inițiat conțin `zsh`:

`procs {{zsh}}`

- Afișează informații despre toate procesele ordonate în funcție de timpul de procesare în ordine [a]scending sau [d]escending:

`procs {{--sortd|--sorta}} cpu`

- Afișează informații despre procesele cu un PID, o comandă sau un utilizator care conține (`zsh` sau `firefox`):

`procs --or {{PID|command|user}} {{41}} {{firefox}}`

- Afișează informații despre procesele care au atât PID `41`, cât și o comandă sau un utilizator care conține `zsh`:

`procs --and {{41}} {{zsh}}`
