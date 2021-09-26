# iptables

> Program care permite configurarea tabelelor, lanțurilor și regulilor furnizate de firewall-ul kernel-ului Linux.
> Mai multe informații: <https://www.netfilter.org/projects/iptables/>.

- Vizualizați lanțurile, regulile și contoarele de pachete/byte pentru tabelul de filtrare:

`sudo iptables -vnL`

- Setați regula de politică a lanțului:

`sudo iptables -P {{chain}} {{rule}}`

- Adăugați o regulă la politica de lanț pentru IP:

`sudo iptables -A {{chain}} -s {{ip}} -j {{rule}}`

- Adăugați o regulă la politica de lanț pentru IP, având în vedere protocolul și portul:

`sudo iptables -A {{chain}} -s {{ip}} -p {{protocol}} --dport {{port}} -j {{rule}}`

- Ștergeți regula lanțului:

`sudo iptables -D {{chain}} {{rule_line_number}}`

- Salvează configurația iptables a unui tabel dat într-un fișier:

`sudo iptables-save -t {{tablename}} > {{path/to/iptables_file}}`

- Restaurați configurația iptables dintr-un fișier:

`sudo iptables-restore < {{path/to/iptables_file}}`
