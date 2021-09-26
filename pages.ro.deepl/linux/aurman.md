# aurman

> Un utilitar Arch Linux pentru a construi și instala pachete din Arch User Repository.
> Vezi și `pacman`.
> Mai multe informații: <https://github.com/polygamma/aurman>.

- Sincronizarea și actualizarea tuturor pachetelor:

`aurman --sync --refresh --sysupgrade`

- Sincronizarea și actualizarea tuturor pachetelor fără a arăta modificări ale fișierelor `PKGBUILD`:

`aurman --sync --refresh --sysupgrade --noedit`

- Instalați un nou pachet:

`aurman --sync {{package_name}}`

- Instalarea unui nou pachet fără a afișa modificări ale fișierelor `PKGBUILD`:

`aurman --sync --noedit {{package_name}}`

- Instalați un nou pachet fără a fi solicitat:

`aurman --sync --noedit --noconfirm {{package_name}}`

- Căutați în baza de date de pachete pentru un cuvânt cheie din depozitele oficiale și AUR:

`aurman --sync --search {{keyword}}`

- Elimină un pachet și dependențele sale:

`aurman --remove --recursive --nosave {{package_name}}`

- Ștergeți memoria cache a pachetelor (folosiți doi indicatori `--clean` pentru a curăța toate pachetele):

`aurman --sync --clean`
