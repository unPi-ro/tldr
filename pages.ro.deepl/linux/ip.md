# ip

> Afișați / manipulați rutarea, dispozitivele, politica de rutare și tunelurile.
> Unele subcomande, cum ar fi `ip address`, au propria documentație de utilizare.
> Mai multe informații: <https://www.man7.org/linux/man-pages/man8/ip.8.html>.

- Lista interfețelor cu informații detaliate:

`ip address`

- Listează interfețele cu informații succinte despre nivelul de rețea:

`ip -brief address`

- Listează interfețele cu informații scurte despre nivelul de legătură:

`ip -brief link`

- Afișați tabelul de rutare:

`ip route`

- Afișează vecinii (tabelul ARP):

`ip neighbour`

- Faceți ca o interfață să fie activată/dezactivată:

`ip link set {{interface}} up/down`

- Adăugarea/ștergerea unei adrese IP la o interfață:

`ip addr add/del {{ip}}/{{mask}} dev {{interface}}`

- Adăugați o rută implicită:

`ip route add default via {{ip}} dev {{interface}}`
