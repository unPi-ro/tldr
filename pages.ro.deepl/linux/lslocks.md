# lslocks

> Listează încuietorile sistemului local.
> Mai multe informații: <https://manned.org/lslocks>.

- Enumeră toate încuietorile sistemului local:

`lslocks`

- Lista de încuietori cu antetele de coloană definite:

`lslocks --output {{PID}},{{COMMAND}},{{PATH}}`

- Încuietori de listă care produc o ieșire brută (fără coloane) și fără antet de coloană:

`lslocks --raw --noheadings`

- Lista încuietorilor în funcție de intrarea PID:

`lslocks --pid {{PID}}`

- Listează încuietorile cu ieșire JSON către stdout:

`lslocks --json`
