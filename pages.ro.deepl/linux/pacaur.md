# pacaur

> Un utilitar pentru Arch Linux pentru a construi și instala pachete din Arch User Repository.

- Sincronizarea și actualizarea tuturor pachetelor (inclusiv AUR):

`pacaur -Syu`

- Sincronizarea și actualizarea numai a pachetelor AUR:

`pacaur -Syua`

- Instalați un nou pachet (include AUR):

`pacaur -S {{package_name}}`

- Elimină un pachet și dependențele sale (inclusiv pachetele AUR):

`pacaur -Rs {{package_name}}`

- Căutați un cuvânt cheie în baza de date a pachetelor (include AUR):

`pacaur -Ss {{keyword}}`

- Listează toate pachetele instalate în prezent (inclusiv pachetele AUR):

`pacaur -Qs`
