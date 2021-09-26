# update-rc.d

> Instalați și eliminați serviciile care sunt legături de scripturi init în stil System-V.
> Scripturile de init sunt în `/etc/init.d/`.
> Mai multe informații: <https://manned.org/update-rc.d>.

- Instalați un serviciu:

`update-rc.d {{mysql}} defaults`

- Activați un serviciu:

`update-rc.d {{mysql}} enable`

- Dezactivați un serviciu:

`update-rc.d {{mysql}} disable`

- Eliminarea forțată a unui serviciu:

`update-rc.d -f {{mysql}} remove`
