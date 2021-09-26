# lshw

> Listați informații detaliate despre configurațiile hardware ca utilizator root.
> Mai multe informații: <https://manned.org/lshw>.

- Lansați GUI:

`sudo lshw -X`

- Enumerați toate echipamentele hardware în format tabelar:

`sudo lshw -short`

- Enumerați toate discurile și controlorii de stocare în format tabelar:

`sudo lshw -class disk -class storage -short`

- Salvați toate interfețele de rețea într-un fișier HTML:

`sudo lshw -class network -html > {{interfaces.html}}`
