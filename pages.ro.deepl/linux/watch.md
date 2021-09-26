# watch

> Executați o comandă în mod repetat și monitorizați rezultatul în modul ecran complet.

- Monitorizează fișierele din directorul curent:

`watch {{ls}}`

- Monitorizați spațiul pe disc și evidențiați modificările:

`watch -d {{df}}`

- Monitorizează procesele "node", actualizând la fiecare 3 secunde:

`watch -n {{3}} "{{ps aux | grep node}}"`
