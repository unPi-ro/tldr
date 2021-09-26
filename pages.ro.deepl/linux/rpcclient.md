# rpcclient

> Instrumentul client MS-RPC (parte a suitei samba).
> Mai multe informații: <https://www.samba.org/samba/docs/current/man-html/rpcclient.1.html>.

- Conectați-vă la o gazdă la distanță:

`rpcclient --user {{domain}}\{{username}}%{{password}} {{ip}}`

- Conectarea la o gazdă la distanță pe un domeniu fără parolă:

`rpcclient --user {{username}} --workgroup {{domain}} --no-pass {{ip}}`

- Se conectează la o gazdă la distanță, trecând parola hash:

`rpcclient --user {{domain}}\{{username}} --pw-nt-hash {{ip}}`

- Executați comenzi shell pe o gazdă la distanță:

`rpcclient --user {{domain}}\{{username}}%{{password}} --command {{semicolon_separated_commands}} {{ip}}`

- Afișează utilizatorii domeniului:

`rpcclient $> enumdomusers`

- Privilegii de afișare:

`rpcclient $> enumprivs`

- Afișează informații despre un anumit utilizator:

`rpcclient $> queryuser {{username|rid}}`

- Creați un nou utilizator în domeniu:

`rpcclient $> createdomuser {{username}}`
