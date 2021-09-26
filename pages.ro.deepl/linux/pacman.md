# pacman

> Utilitarul de gestionare a pachetelor Arch Linux.
> Unele subcomandă, cum ar fi `pacman sync`, au propria lor documentație de utilizare.
> Mai multe informații: <https://man.archlinux.org/man/pacman.8>.

- Sincronizarea și actualizarea tuturor pachetelor:

`pacman --sync --refresh --sysupgrade`

- Instalați un nou pachet:

`pacman --sync {{package_name}}`

- Elimină un pachet și dependențele sale:

`pacman --remove --recursive {{package_name}}`

- Căutați în baza de date a pachetelor o expresie regulată sau un cuvânt cheie:

`pacman --sync --search "{{search_pattern}}"`

- Listează pachetele și versiunile instalate:

`pacman --query`

- Enumeră numai pachetele și versiunile instalate în mod explicit:

`pacman --query --explicit`

- Listează pachetele orfane (instalate ca dependențe, dar care nu sunt de fapt solicitate de niciun pachet):

`pacman --query --unrequired --deps --quiet`

- Goliți întreaga memorie cache pacman:

`pacman --sync --clean --clean`
