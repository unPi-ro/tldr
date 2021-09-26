# journalctl

> Consultați jurnalul systemd.
> Mai multe informații: <https://manned.org/journalctl>.

- Afișați toate mesajele din acest [b]oot:

`journalctl -b`

- Afișează toate mesajele de la ultimul [b]oot:

`journalctl -b -1`

- Afișează toate mesajele cu nivelul de prioritate 3 (erori) din acest [b]oot:

`journalctl -b --priority={{3}}`

- [f]olow new messages (ca `tail -f` pentru syslog tradițional):

`journalctl -f`

- Afișează toate mesajele de către un anumit [u]nit:

`journalctl -u {{unit}}`

- Filtrează mesajele dintr-un interval de timp (fie că este vorba de o marcă temporală, fie că este vorba de caractere de siguranță precum "ieri"):

`journalctl --since {{now|today|yesterday|tomorrow}} --until {{YYYY-MM-DD HH:MM:SS}}`

- Afișează toate mesajele unui anumit proces:

`journalctl _PID={{pid}}`

- Afișează toate mesajele unui anumit executabil:

`journalctl {{path/to/executable}}`
