# pamac

> Un utilitar în linie de comandă pentru managerul de pachete GUI pamac.
> Dacă nu puteți vedea pachetele AUR, activați-le în `/etc/pamac.conf` sau în GUI.
> More information: <https://wiki.manjaro.org/index.php/Pamac>.

- Instalați un nou pachet:

`pamac install {{package_name}}`

- Îndepărtați un pachet și dependențele sale care nu mai sunt necesare (orfani):

`pamac remove --orphans {{package_name}}`

- Căutați un pachet în baza de date a pachetelor:

`pamac search {{package_name}}`

- Lista pachetelor instalate:

`pamac list --installed`

- Verificați dacă există actualizări de pachete:

`pamac checkupdates`

- Actualizați toate pachetele:

`pamac upgrade`
