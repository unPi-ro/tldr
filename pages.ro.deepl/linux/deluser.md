# deluser

> Ștergeți un utilizator din sistem.
> Notă: toate comenzile trebuie să fie executate ca root.
> Mai multe informații: <https://manpages.debian.org/latest/adduser/deluser.html>.

- Eliminați un utilizator:

`deluser {{username}}`

- Eliminați un utilizator și directorul său principal:

`deluser --remove-home {{username}}`

- Elimină un utilizator și casa acestuia, dar face o copie de rezervă a fișierelor sale într-un fișier `.tar.gz` în directorul specificat:

`deluser --backup-to {{path/to/backup_directory}} --remove-home {{username}}`

- Elimină un utilizator și toate fișierele deținute de acesta:

`deluser --remove-all-files {{username}}`
