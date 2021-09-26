# pacman --sync

> Utilitarul de gestionare a pachetelor Arch Linux.
> Mai multe informații: <https://man.archlinux.org/man/pacman.8>.

- Instalați un nou pachet:

`sudo pacman --sync {{package_name}}`

- Sincronizați și actualizați toate pachetele (adăugați `--downloadonly` pentru a descărca pachetele și a nu le actualiza):

`sudo pacman --sync --refresh --sysupgrade`

- Actualizați toate pachetele și instalați unul nou fără a fi solicitați:

`sudo pacman --sync --refresh --sysupgrade --noconfirm {{package_name}}`

- Căutați în baza de date a pachetelor o expresie regulată sau un cuvânt cheie:

`pacman --sync --search "{{search_pattern}}"`

- Afișează informații despre un pachet:

`pacman --sync --info {{package_name}}`

- Suprascrieți fișierele conflictuale în timpul actualizării unui pachet:

`sudo pacman --sync --refresh --sysupgrade --overwrite {{path/to/file}}`

- Sincronizează și actualizează toate pachetele, dar ignoră un anumit pachet (poate fi utilizat de mai multe ori):

`sudo pacman --sync --refresh --sysupgrade --ignore {{package_name}}`

- Elimină din memoria cache pachetele neinstalate și depozitele nefolosite (folosiți doi indicatori `--clean` pentru a curăța toate pachetele):

`sudo pacman --sync --clean`
