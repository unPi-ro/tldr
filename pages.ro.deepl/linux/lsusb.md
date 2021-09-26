# lsusb

> Afișați informații despre autobuzele USB și dispozitivele conectate la acestea.
> Mai multe informații: <https://manned.org/lsusb>.

- Enumerați toate dispozitivele USB disponibile:

`lsusb`

- Enumerați ierarhia USB sub forma unui arbore:

`lsusb -t`

- Enumeră informații detaliate despre dispozitivele USB:

`lsusb --verbose`

- Enumeră informații detaliate despre un dispozitiv USB:

`lsusb -D {{device}}`

- Listează numai dispozitivele cu un furnizor și un ID de produs specificate:

`lsusb -d {{vendor}}:{{product}}`
