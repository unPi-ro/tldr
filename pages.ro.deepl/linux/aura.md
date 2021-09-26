# aura

> Managerul de pachete Aura: Un manager de pachete securizat și multilingv pentru Arch Linux și AUR.
> Mai multe informații: <https://github.com/fosskers/aura>.

- Căutați pachete din depozitele oficiale și AUR:

`aura --aursync --both --search {{package_name|search_regex}}`

- Instalați un pachet din AUR:

`aura --aursync {{package_name}}`

- Actualizează toate pachetele AUR în modul "verbose" și elimină toate dependențele make:

`aura --aursync --diff --sysupgrade --delmakedeps --unsuppress`

- Instalați un pachet din depozitele oficiale:

`aura --sync {{package_name}}`

- Sincronizarea și actualizarea tuturor pachetelor din depozitele oficiale:

`aura --sync --refresh --sysupgrade`

- Retrogradează un pachet folosind memoria cache a pachetului:

`aura --downgrade {{package_name}}`

- Elimină un pachet și dependențele sale:

`aura --remove --recursive --unneeded {{package_name}}`

- Îndepărtați pachetele orfane (instalate ca dependențe, dar care nu sunt solicitate de niciun pachet):

`aura --orphans --abandon`
