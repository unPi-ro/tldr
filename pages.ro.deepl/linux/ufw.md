# ufw

> Firewall necomplicat.
> Frontend pentru iptables cu scopul de a face mai ușoară configurarea unui firewall.
> Mai multe informații: <https://wiki.ubuntu.com/UncomplicatedFirewall>.

- Activați ufw:

`ufw enable`

- Dezactivați ufw:

`ufw disable`

- Afișează regulile ufw, împreună cu numerele acestora:

`ufw status numbered`

- Permiteți traficul de intrare pe portul 5432 pe această gazdă cu un comentariu care identifică serviciul:

`ufw allow {{5432}} comment "{{Service}}"`

- Permiteți numai traficul TCP de la 192.168.0.4 către orice adresă de pe această gazdă, pe portul 22:

`ufw allow proto {{tcp}} from {{192.168.0.4}} to {{any}} port {{22}}`

- Refuzați traficul pe portul 80 pe această gazdă:

`ufw deny {{80}}`

- Refuzați tot traficul UDP către portul 22:

`ufw deny proto {{udp}} from {{any}} to {{any}} port {{22}}`

- Ștergeți o anumită regulă. Numărul regulii poate fi recuperat din comanda `ufw status numbered`:

`ufw delete {{rule_number}}`
