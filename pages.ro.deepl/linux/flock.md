# flock

> Gestionați încuietorile din scripturi shell.
> Poate fi utilizat pentru a se asigura că doar un singur proces al unei comenzi este în curs de execuție.
> Mai multe informații: <https://manned.org/flock>.

- Executați o comandă cu un fișier blocat imediat ce blocajul nu este solicitat de alte persoane:

`flock {{path/to/lock.lock}} --command "{{command}}"`

- Execută o comandă cu un fișier blocat și iese dacă blocajul nu există:

`flock {{path/to/lock.lock}} --nonblock --command "{{command}}"`

- Executați o comandă cu un fișier blocat și ieșiți cu un cod de eroare specific dacă blocajul nu există:

`flock {{path/to/lock.lock}} --nonblock --conflict-exit-code {{error_code}} -c "{{command}}"`
