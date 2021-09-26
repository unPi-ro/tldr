# edquota

> Editați cotele pentru un utilizator sau un grup. În mod implicit, funcționează pe toate sistemele de fișiere cu cote.
> Informațiile privind cotele sunt stocate permanent în fișierele `quota.user` și `quota.group` din rădăcina sistemului de fișiere.
> Mai multe informații: <https://manned.org/edquota>.

- Editează cota utilizatorului curent:

`edquota --user $(whoami)`

- Editați cota unui anumit utilizator:

`sudo edquota --user {{username}}`

- Editați cota pentru un grup:

`sudo edquota --group {{group}}`

- Restricționează operațiunile la un anumit sistem de fișiere (în mod implicit, edquota operează pe toate sistemele de fișiere cu cote):

`sudo edquota --file-system {{filesystem}}`

- Modificați perioada de grație implicită:

`sudo edquota -t`

- Duplicarea unei cote pentru alți utilizatori:

`sudo edquota -p {{reference_user}} {{destination_user1}} {{destination_user2}}`
