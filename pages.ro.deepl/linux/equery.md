# equery

> Vizualizați informații despre pachetele Portage.
> Mai multe informații: <https://wiki.gentoo.org/wiki/Equery>.

- Listează toate pachetele instalate:

`equery list '*'`

- Căutați pachetele instalate în arborele Portage și în suprapuneri:

`equery list -po {{package_name}}`

- Enumeră toate pachetele care depind de un anumit pachet:

`equery depends {{package_name}}`

- Enumeră toate pachetele de care depinde un anumit pachet:

`equery depgraph {{package_name}}`

- Listează toate fișierele instalate de un pachet:

`equery files --tree {{package_name}}`
