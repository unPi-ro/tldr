# systemd-analyze

> Afișează detalii de sincronizare despre procesul de pornire a unităților (servicii, puncte de montare, dispozitive, socket-uri).

- Enumerați timpul de pornire a fiecărei unități:

`systemd-analyze blame`

- Tipărește un arbore al lanțului de unități critice din punct de vedere al timpului:

`systemd-analyze critical-chain`

- Creați un fișier SVG care să arate momentul în care fiecare serviciu de sistem a pornit, evidențiind timpul pe care l-au petrecut la inițializare:

`systemd-analyze plot > {{path/to/file.svg}}`

- Trasați un grafic de dependență și convertiți-l într-un fișier SVG:

`systemd-analyze dot | dot -T{{svg}} > {{path/to/file.svg}}`
