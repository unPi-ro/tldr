# pacman --remove

> Utilitarul de gestionare a pachetelor Arch Linux.
> Mai multe informații: <https://man.archlinux.org/man/pacman.8>.

- Afișează ajutorul pentru această subcomandă:

`pacman --remove --help`

- Elimină un pachet și dependențele sale:

`sudo pacman --remove --recursive {{package_name}}`

- Îndepărtați un pachet și atât dependențele sale, cât și fișierele de configurare:

`sudo pacman --remove --recursive --nosave {{package_name}}`

- Îndepărtați un pachet fără a fi solicitați:

`sudo pacman --remove --noconfirm {{package_name}}`

- Îndepărtați pachetele orfane (instalate ca dependențe, dar care nu sunt solicitate de niciun pachet):

`sudo pacman --remove --recursive --nosave $(pacman --query --unrequired --deps --quiet)`

- Elimină un pachet și toate pachetele care depind de el:

`sudo pacman --remove --cascade {{package_name}}`

- Enumeră pachetele care ar fi afectate (nu elimină niciun pachet):

`pacman --remove --print {{package_name}}`
