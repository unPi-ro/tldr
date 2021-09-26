# ldapdomaindump

> Aruncă utilizatorii, computerele, grupurile, sistemele de operare și informațiile de apartenență prin LDAP în format HTML, JSON și în format greppable.
> Vezi și `ldapsearch`.
> Mai multe informații: <https://github.com/dirkjanm/ldapdomaindump>.

- Aruncă toate informațiile care utilizează contul LDAP dat:

`ldapdomaindump --user {{domain}}\\{{administrator}} --password {{password|ntlm_hash}} {{hostname|ip}}`

- Aruncă toate informațiile, rezolvând numele de gazdă ale calculatoarelor:

`ldapdomaindump --resolve --user {{domain}}\\{{administrator}} --password {{password}} {{hostname|ip}}`

- Aruncă toate informațiile, rezolvând numele de gazdă ale computerului cu serverul DNS selectat:

`ldapdomaindump --resolve --dns-server {{domain_controller_ip}} --user {{domain}}\\{{administrator}} --password {{password}} {{hostname|ip}}`

- Aruncă toate informațiile în directorul dat, fără ieșire JSON:

`ldapdomaindump --no-json --outdir {{path/to/directory}} --user {{domain}}\\{{administrator}} --password {{password}} {{hostname|ip}}`
