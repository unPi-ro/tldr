# genid

> Generați ID-uri, cum ar fi fulgi de zăpadă, UUID-uri și un nou GAID.
> Mai multe informații: <https://github.com/bleonard252/genid>.

- Generați un UUIDv4:

`genid uuid`

- Generează un UUIDv5 utilizând un UUID de spațiu de nume și un nume specific:

`genid uuidv5 {{{ce598faa-8dd0-49ee-8525-9e24fff71dca}}} {{name}}`

- Generează un fulg de zăpadă Discord, fără o linie nouă la sfârșit (util în scripturile shell):

`genid --script snowflake`

- Generarea unui ID generic anonim cu un "ID real" specific:

`genid gaid {{real_id}}`

- Generează un fulg de zăpadă cu epoca setată la o anumită dată:

`genid snowflake --epoch={{unix_epoch_time}}`
