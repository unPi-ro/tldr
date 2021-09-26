# ebuild

> O interfață de nivel scăzut pentru sistemul Gentoo Portage.
> Mai multe informații: <https://wiki.gentoo.org/wiki/Ebuild>.

- Creați sau actualizați manifestul pachetului:

`ebuild {{path/to/file.ebuild}} manifest`

- Curățați directoarele temporare de construcție pentru fișierul de construcție:

`ebuild {{path/to/file.ebuild}} clean`

- Preluarea surselor dacă acestea nu există:

`ebuild {{path/to/file.ebuild}} fetch`

- Extrageți sursele într-un director temporar de construcție:

`ebuild {{path/to/file.ebuild}} unpack`

- Compilați sursele extrase:

`ebuild {{path/to/file.ebuild}} compile`

- Instalați pachetul într-un director de instalare temporar:

`ebuild {{path/to/file.ebuild}} install`

- Instalați fișierele temporare în sistemul de fișiere activ:

`ebuild {{path/to/file.ebuild}} qmerge`

- Preia, despachetează, compilează, instalează și qmerge fișierul ebuild specificat:

`ebuild {{path/to/file.ebuild}} merge`
