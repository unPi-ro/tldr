# trizen

> Utilitar Arch Linux pentru construirea de pachete din Arch User Repository (AUR).
> Mai multe informații: <https://github.com/trizen/trizen>.

- Sincronizarea și actualizarea tuturor pachetelor AUR:

`trizen -Syua`

- Instalați un nou pachet:

`trizen -S {{package}}`

- Elimină un pachet și dependențele sale:

`trizen -Rs {{package}}`

- Căutați un cuvânt cheie în baza de date a pachetelor:

`trizen -Ss {{keyword}}`

- Afișează informații despre un pachet:

`trizen -Si {{package}}`

- Listează pachetele și versiunile instalate:

`trizen -Qe`
