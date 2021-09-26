# makepkg

> Creează un pachet care poate fi instalat cu managerul de pachete `pacman`.
> Execută comenzile dintr-un fișier `PKGBUILD` pentru a construi pachetul.
> Mai multe informații: <https://man.archlinux.org/man/makepkg.8>.

- Creează un pachet (se execută în același director ca și `PKGBUILD`):

`makepkg`

- Creați un pachet și instalați dependențele sale:

`makepkg --syncdeps`

- La fel ca mai sus, dar instalați pachetul cu `pacman` când ați terminat:

`makepkg --syncdeps --install`

- Creați un pachet, dar săriți peste verificările sursei:

`makepkg --skipchecksums`

- Curățați directoarele de lucru după o construcție reușită:

`makepkg --clean`
