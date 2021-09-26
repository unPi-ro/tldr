# ipset

> Un instrument pentru a crea seturi de IP pentru regulile de firewall.
> Mai multe informații: <https://manned.org/ipset>.

- Creați un set IP gol care va conține adrese IP:

`ipset create {{set_name}} hash:ip`

- Distruge un anumit set de IP:

`ipset destroy {{set_name}}`

- Adăugați o adresă IP la un set specific:

`ipset add {{set_name}} {{192.168.1.25}}`

- Ștergeți o anumită adresă IP dintr-un set:

`ipset del {{set_name}} {{192.168.1.25}}`

- Salvați un set IP:

`ipset save {{set_name}} > {{path/to/ip_set}}`
