# apt-key

> Utilitar de gestionare a cheilor pentru APT Package Manager pe Debian și Ubuntu.
> Notă: `apt-key` este acum depreciat (cu excepția utilizării lui `apt-key del` în scripturile de întreținere).
> Mai multe informații: <https://manpages.debian.org/latest/apt/apt-key.8.html>.

- Lista cheilor de încredere:

`apt-key list`

- Adăugați o cheie la depozitul de chei de încredere:

`apt-key add {{public_key_file.asc}}`

- Ștergeți o cheie din depozitul de chei de încredere:

`apt-key del {{key_id}}`

- Adăugați o cheie de la distanță la depozitul de chei de încredere:

`wget -qO - {{https://host.tld/filename.key}} | apt-key add -`

- Adăugați o cheie de la serverul de chei doar cu ID-ul cheii:

`apt-key adv --keyserver {{pgp.mit.edu}} --recv {{KEYID}}`
