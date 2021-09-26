# pacman --upgrade

> Utilitarul de gestionare a pachetelor Arch Linux.
> Mai multe informații: <https://man.archlinux.org/man/pacman.8>.

- Ajutor pentru afișare:

`pacman --upgrade --help`

- Instalează unul sau mai multe pachete din fișiere:

`sudo pacman --upgrade {{path/to/package1.pkg.tar.zst}} {{path/to/package2.pkg.tar.zst}}`

- Instalați un pachet fără a fi solicitat:

`sudo pacman --upgrade --noconfirm {{path/to/package.pkg.tar.zst}}`

- Suprascrieți fișierele conflictuale în timpul instalării unui pachet:

`sudo pacman --upgrade --overwrite {{path/to/file}} {{path/to/package.pkg.tar.zst}}`

- Instalează un pachet, sărind peste verificările versiunilor de dependență:

`sudo pacman --upgrade --nodeps {{path/to/package.pkg.tar.zst}}`

- Listează pachetele care ar fi afectate (nu instalează niciun pachet):

`pacman --query --print {{path/to/package.pkg.tar.zst}}`
