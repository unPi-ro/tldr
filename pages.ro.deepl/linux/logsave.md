# logsave

> Salvați ieșirea unei comenzi într-un fișier jurnal.
> Mai multe informații: <https://manned.org/logsave>.

- Execută comanda cu argumentul (argumentele) specificat(e) și salvează rezultatul acesteia în fișierul jurnal:

`logsave {{path/to/logfile}} {{command}}`

- Preia datele de intrare de la intrarea standard și le salvează într-un fișier jurnal:

`logsave {{logfile}} -`

- Adăugați rezultatul la un fișier jurnal, în loc să înlocuiți conținutul curent al acestuia:

`logsave -a {{logfile}} {{command}}`

- Afișează ieșirea verbose:

`logsave -v {{logfile}} {{command}}`
