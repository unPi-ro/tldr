# ss

> Utilitar pentru a investiga prize.
> Mai multe informații: <https://manned.org/ss.8>.

- Afișează toate socket-urile TCP/UDP/RAW/UNIX:

`ss -a {{-t|-u|-w|-x}}`

- Filtrează socket-urile TCP în funcție de stări, numai/exclude:

`ss {{state/exclude}} {{bucket/big/connected/synchronized/...}}`

- Afișează toate socketurile TCP conectate la portul HTTPS local (443):

`ss -t src :{{443}}`

- Afișează toate socket-urile TCP care ascultă pe portul local 8080:

`ss -lt src :{{8080}}`

- Afișează toate socket-urile TCP împreună cu procesele conectate la un port ssh de la distanță:

`ss -pt dst :{{ssh}}`

- Afișează toate soclurile UDP conectate pe anumite porturi sursă și destinație:

`ss -u 'sport == :{{source_port}} and dport == :{{destination_port}}'`

- Afișează toate socket-urile TCP IPv4 conectate local în subrețeaua 192.168.0.0/16:

`ss -4t src {{192.168/16}}`
