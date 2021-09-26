# xbps

> Sistemul de pachete binare X (sau xbps) este sistemul de pachete binare folosit de Void Linux.
> Mai multe informații: <https://github.com/void-linux/xbps>.

- Instalarea pachetelor și sincronizarea acestora cu depozitul de la distanță:

`xbps-install --synchronize {{package_name1}} {{package_name2}}`

- Căutați un pachet în depozitul la distanță:

`xbps-query --repository -s {{package_name}}`

- Elimină un pachet, lăsând toate dependențele sale instalate:

`xbps-remove {{package_name}}`

- Elimină un pachet și toate dependențele sale în mod recursiv, care nu sunt solicitate de alte pachete:

`xbps-remove --recursive {{package_name}}`

- Sincronizați bazele de date ale depozitului și actualizați-vă sistemul și dependențele:

`xbps-install --synchronize -u`

- Îndepărtați pachetele care au fost instalate ca dependențe și care nu sunt necesare în prezent:

`xbps-remove --remove-orphans`

- Elimină pachetele învechite din memoria cache:

`xbps-remove --clean-cache`
