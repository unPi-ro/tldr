# paru

> Un ajutor pentru AUR și o învelitoare pentru pacman.
> Mai multe informații: <https://github.com/Morganamilo/paru>.

- Căutați și instalați un pachet în mod interactiv:

`paru {{package_name_or_seach_term}}`

- Sincronizarea și actualizarea tuturor pachetelor:

`paru`

- Actualizați pachetele AUR:

`paru -Sua`

- Obțineți informații despre un pachet:

`paru -Si {{package_name}}`

- Descărcați `PKGBUILD` și alte fișiere sursă ale pachetelor de pe AUR sau ABS:

`paru --getpkgbuild {{package_name}}`

- Afișează fișierul `PKGBUILD` al unui pachet:

`paru --getpkgbuild --print {{package_name}}`
