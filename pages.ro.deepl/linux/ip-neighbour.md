# ip-neighbour

> Gestionarea tabelelor de vecinătate/ARP Subcomanda IP.
> Mai multe informații: <https://manned.org/ip-neighbour.8>.

- Afișează intrările din tabelul vecinilor/ARP:

`ip neighbour`

- Eliminați intrările din tabelul de vecini de pe dispozitivul `eth0`:

`sudo ip neighbour flush dev {{eth0}}`

- Efectuează o căutare a vecinilor și trimite o intrare de vecinătate:

`ip neighbour get {{lookup_ip}} dev {{eth0}}`

- Adăugați sau ștergeți o intrare ARP pentru adresa IP a vecinului `eth0`:

`sudo ip neighbour {{add|del}} {{ip_address}} lladdr {{mac_address}} dev {{eth0}} nud reachable`

- Modificați sau înlocuiți o intrare ARP pentru adresa IP a vecinului `eth0`:

`sudo ip neighbour {{change|replace}} {{ip_address}} lladdr {{new_mac_address}} dev {{eth0}}`
