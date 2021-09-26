# emerge

> Utilitarul de gestionare a pachetelor Gentoo Linux.
> Mai multe informații: <https://wiki.gentoo.org/wiki/Portage#emerge>.

- Sincronizați toate pachetele:

`emerge --sync`

- Actualizați toate pachetele, inclusiv dependențele:

`emerge -uDNav @world`

- Reluarea unei actualizări eșuate, sărind peste pachetul eșuat:

`emerge --resume --skipfirst`

- Instalați un nou pachet, cu confirmare:

`emerge -av {{package_name}}`

- Îndepărtarea unui pachet, cu confirmare:

`emerge -Cav {{package_name}}`

- Îndepărtați pachetele orfane (care au fost instalate doar ca dependențe):

`emerge -avc`

- Căutați un cuvânt cheie în baza de date a pachetelor:

`emerge -S {{keyword}}`
