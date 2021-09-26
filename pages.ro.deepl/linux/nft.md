# nft

> Permite configurarea tabelelor, lanțurilor și regulilor furnizate de firewall-ul kernel-ului Linux.
> Nftables înlocuiește iptables.

- Vizualizați configurația curentă:

`sudo nft list ruleset`

- Adăugați un nou tabel cu familia "inet" și tabelul "filter":

`sudo nft add table {{inet}} {{filter}}`

- Adăugați un nou lanț pentru a accepta tot traficul de intrare:

`sudo nft add chain {{inet}} {{filter}} {{input}} \{ type {{filter}} hook {{input}} priority {{0}} \; policy {{accept}} \}`

- Adăugați o nouă regulă pentru a accepta mai multe porturi TCP:

`sudo nft add rule {{inet}} {{filter}} {{input}} {{tcp}} {{dport \{ telnet, ssh, http, https \} accept}}`

- Afișați mânerele regulilor:

`sudo nft --handle --numeric list chain {{family}} {{table}} {{chain}}`

- Ștergeți o regulă:

`sudo nft delete rule {{inet}} {{filter}} {{input}} handle {{3}}`

- Salvează configurația curentă:

`sudo nft list ruleset > {{/etc/nftables.conf}}`
