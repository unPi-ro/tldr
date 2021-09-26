# eix

> Utilități pentru căutarea pachetelor Gentoo locale.
> Actualizați memoria cache a pachetelor locale folosind `eix-update`.
> Mai multe informații: <https://wiki.gentoo.org/wiki/Eix>.

- Căutați un pachet:

`eix {{package_name}}`

- Căutați pachetele instalate:

`eix --installed {{package_name}}`

- Căutați în descrierile pachetelor:

`eix --description "{{description}}"`

- Căutați după licența pachetului:

`eix --license {{license}}`

- Excludeți rezultatele din căutare:

`eix --not --license {{license}}`
