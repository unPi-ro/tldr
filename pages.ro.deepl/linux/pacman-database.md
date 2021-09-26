# pacman --database

> Operați pe baza de date a pachetelor Arch Linux.
> Modificați anumite atribute ale pachetelor instalate.
> Mai multe informații: <https://man.archlinux.org/man/pacman.8>.

- Ajutor pentru afișare:

`pacman --database --help`

- Marchează un pachet ca fiind instalat implicit:

`sudo pacman --database --asdeps {{package_name}}`

- Marchează un pachet ca fiind instalat în mod explicit:

`sudo pacman --database --asexplicit {{package_name}}`

- Verificați dacă sunt instalate toate dependențele pachetului:

`pacman --database --check`

- Verificați depozitele pentru a vă asigura că toate dependențele specificate sunt disponibile:

`pacman --database --check --check`

- Afișează numai mesajele de eroare:

`pacman --database --check --quiet`
