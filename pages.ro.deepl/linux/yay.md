# yay

> Încă un iaurt: Un utilitar pentru Arch Linux pentru a construi și instala pachete din Arch User Repository.
> Vezi și `pacman`.
> Mai multe informații: <https://github.com/Jguer/yay>.

- Căutați și instalați interactiv pachete din depozite și AUR:

`yay {{package_name|search_term}}`

- Sincronizarea și actualizarea tuturor pachetelor din depozite și AUR:

`yay`

- Sincronizarea și actualizarea numai a pachetelor AUR:

`yay -Sua`

- Instalați un nou pachet din depozite și AUR:

`yay -S {{package_name}}`

- Îndepărtați un pachet instalat, precum și dependențele și fișierele de configurare ale acestuia:

`yay -Rns {{package_name}}`

- Căutați în baza de date a pachetelor un cuvânt cheie din depozite și AUR:

`yay -Ss {{keyword}}`

- Îndepărtați pachetele orfane (instalate ca dependențe, dar care nu sunt solicitate de niciun pachet):

`yay -Yc`

- Afișează statisticile privind pachetele instalate și starea de sănătate a sistemului:

`yay -Ps`
