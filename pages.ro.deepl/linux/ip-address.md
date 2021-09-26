# ip address

> Subcomanda de gestionare a adreselor IP.
> Mai multe informații: <https://manned.org/ip-address>.

- Listează interfețele de rețea și adresele IP asociate acestora:

`ip address`

- Filtrează pentru a afișa numai interfețele de rețea active:

`ip address show up`

- Afișează informații despre o anumită interfață de rețea:

`ip address show dev {{eth0}}`

- Adăugați o adresă IP la o interfață de rețea:

`ip address add {{ip_address}} dev {{eth0}}`

- Îndepărtați o adresă IP de pe o interfață de rețea:

`ip address delete {{ip_address}} dev {{eth0}}`

- Șterge toate adresele IP dintr-o interfață de rețea dintr-o anumită sferă:

`ip address flush dev {{eth0}} scope {{global|host|link}}`
