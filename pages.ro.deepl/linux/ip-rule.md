# ip rule

> Gestionarea bazei de date a politicilor de rutare IP.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/ip-rule.8.html>.

- Afișați politica de rutare:

`ip rule {{show|list}}`

- Adăugați o nouă regulă bazată pe adresele sursă ale pachetelor:

`sudo ip rule add from {{192.168.178.2/32}}`

- Adăugați o nouă regulă bazată pe adresele de destinație ale pachetelor:

`sudo ip rule add to {{192.168.178.2/32}}`

- Ștergeți o regulă bazată pe adresele sursă ale pachetelor:

`sudo ip rule delete from {{192.168.178.2/32}}`

- Ștergeți o regulă bazată pe adresele de destinație a pachetelor:

`sudo ip rule delete to {{192.168.178.2/32}}`

- Ștergeți toate regulile șterse:

`ip rule flush`

- Salvați toate regulile într-un fișier:

`ip rule save > {{path/to/ip_rules.dat}}`

- Restabilește toate regulile dintr-un fișier:

`ip rule restore < {{path/to/ip_rules.dat}}`
