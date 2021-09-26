# synoupgrade

> Actualizați un Synology DiskStation Manager (DSM) din linia de comandă.
> Mai multe informații: <https://www.synology.com/dsm>.

- Verificați dacă sunt disponibile actualizări:

`sudo synoupgrade --check`

- Verificați dacă există patch-uri fără a actualiza versiunea DSM:

`sudo synoupgrade --check-smallupdate`

- Descărcați cea mai recentă actualizare disponibilă (utilizați `--download-smallupdate` pentru patch-uri):

`sudo synoupgrade --download`

- Începeți procesul de actualizare:

`sudo synoupgrade --start`

- Actualizați automat la cea mai recentă versiune:

`sudo synoupgrade --auto`

- Aplicați patch-uri fără a actualiza automat versiunea DSM:

`sudo synoupgrade --auto-smallupdate`

- Actualizați DSM utilizând un fișier patch (ar trebui să fie o cale absolută):

`sudo synoupgrade --patch {{/path/to/file.pat}}`

- Ajutor pentru afișare:

`synoupgrade`
