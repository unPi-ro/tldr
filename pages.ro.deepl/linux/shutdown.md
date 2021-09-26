# shutdown

> Opriți și reporniți sistemul.

- Opriți (opriți) imediat:

`shutdown -h now`

- Reporniți imediat:

`shutdown -r now`

- Repornire în 5 minute:

`shutdown -r +{{5}} &`

- Închidere la ora 13:00 (ora de 24 de ore):

`shutdown -h 13:00`

- Anulează o operațiune de închidere/repornire în așteptare:

`shutdown -c`
