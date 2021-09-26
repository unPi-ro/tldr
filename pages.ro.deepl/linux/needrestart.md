# needrestart

> Verificați ce demoni trebuie reporniți după actualizarea bibliotecilor.
> Mai multe informații: <https://github.com/liske/needrestart>.

- Lista proceselor depășite:

`needrestart`

- Repornirea interactivă a serviciilor:

`sudo needrestart`

- Listează procesele depășite în modul [v]erbose sau [q]uiet:

`needrestart -{{v|q}}`

- Verificați dacă [k]ernel-ul este depășit:

`needrestart -k`

- Verificați dacă microcodul procesorului este depășit:

`needrestart -w`

- Lista proceselor depășite în modul [b]atch:

`needrestart -b`

- Listă de date depășite procesate utilizând un fișier [c]onfigurare specific:

`needrestart -c {{path/to/config}}`

- Ajutor pentru afișare:

`needrestart --help`
