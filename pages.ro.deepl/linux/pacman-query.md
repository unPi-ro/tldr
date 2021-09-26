# pacman --query

> Utilitarul de gestionare a pachetelor Arch Linux.
> Mai multe informații: <https://man.archlinux.org/man/pacman.8>.

- Listează pachetele și versiunile instalate:

`pacman --query`

- Enumeră numai pachetele și versiunile care au fost instalate în mod explicit:

`pacman --query --explicit`

- Află ce pachet deține un fișier:

`pacman --query --owns {{filename}}`

- Afișează informații despre un pachet instalat:

`pacman --query --info {{package_name}}`

- Listează fișierele deținute de un pachet:

`pacman --query --list {{package_name}}`

- Listează pachetele orfane (instalate ca dependențe, dar care nu sunt solicitate de niciun pachet):

`pacman --query --unrequired --deps --quiet`

- Listează pachetele instalate care nu se găsesc în depozite:

`pacman --query --foreign`

- Lista pachetelor depășite:

`pacman --query --upgrades`
