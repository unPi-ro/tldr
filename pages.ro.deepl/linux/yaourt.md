# yaourt

> Utilitar Arch Linux pentru construirea de pachete din Arch User Repository.

- Sincronizarea și actualizarea tuturor pachetelor (inclusiv AUR):

`yaourt -Syua`

- Instalați un nou pachet (include AUR):

`yaourt -S {{package_name}}`

- Elimină un pachet și dependențele sale (inclusiv pachetele AUR):

`yaourt -Rs {{package_name}}`

- Căutați în baza de date a pachetelor un cuvânt cheie (inclusiv AUR):

`yaourt -Ss {{package_name}}`

- Listează pachetele, versiunile și depozitele instalate (pachetele AUR vor fi listate sub numele de depozit "local"):

`yaourt -Q`
