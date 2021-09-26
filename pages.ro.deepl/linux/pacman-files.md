# pacman --files

> Utilitarul de gestionare a pachetelor Arch Linux.
> Vezi și `pkgfile`.
> Mai multe informații: <https://man.archlinux.org/man/pacman.8>.

- Ajutor pentru afișare:

`pacman --files --help`

- Actualizarea bazei de date a pachetelor:

`sudo pacman --files --refresh`

- Găsiți pachetul care deține un anumit fișier:

`pacman --files {{filename}}`

- Găsește pachetul care deține un anumit fișier, utilizând o expresie regulată:

`pacman --files --regex '{{regular_expression}}'`

- Enumeră numai numele pachetelor:

`pacman --files --quiet {{filename}}`

- Enumeră fișierele deținute de un anumit pachet:

`pacman --files --list {{package_name}}`

- Enumeră numai calea absolută către fișiere:

`pacman --query --list --quiet {{package_name}}`
