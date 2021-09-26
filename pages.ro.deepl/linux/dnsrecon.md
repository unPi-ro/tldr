# dnsrecon

> Instrument de enumerare DNS.
> Mai multe informații: <https://github.com/darkoperator/dnsrecon>.

- Scanează un domeniu și salvează rezultatele într-o bază de date SQLite:

`dnsrecon --domain {{example.com}} --db {{path/to/database.sqlite}}`

- Scanarea unui domeniu, specificarea serverului de nume și efectuarea unui transfer de zonă:

`dnsrecon --domain {{example.com}} --name_server {{nameserver.example.com}} --type axfr`

- Scanați un domeniu, utilizând un atac prin forță brută și un dicționar de subdomenii și nume de gazdă:

`dnsrecon --domain {{example.com}} --dictionary {{path/to/dictionary.txt}} --type brt`

- Scanează un domeniu, efectuând o căutare inversă a intervalelor IP din înregistrarea SPF și salvând rezultatele într-un fișier JSON:

`dnsrecon --domain {{example.com}} -s --json`

- Scanează un domeniu, efectuând o enumerare Google și salvând rezultatele într-un fișier CSV:

`dnsrecon --domain {{example.com}} -g --csv`

- Scanează un domeniu, efectuând DNS cache snooping:

`dnsrecon --domain {{example.com}} --type snoop --name_server {{nameserver.example.com}} --dictionary {{path/to/dictionary.txt}}`

- Scanează un domeniu, efectuând mersul pe zone:

`dnsrecon --domain {{example.com}} --type zonewalk`
