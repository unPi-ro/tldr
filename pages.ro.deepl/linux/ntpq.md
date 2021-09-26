# ntpq

> Interoghează demonul Network Time Protocol (NTP).
> Mai multe informații: <https://www.eecis.udel.edu/~mills/ntp/html/ntpq.html>.

- Pornește `ntpq` în modul interactiv:

`ntpq --interactive`

- Tipărește o listă de omologi NTP:

`ntpq --peers`

- Tipărește o listă de omologi NTP fără a rezolva numele de gazdă din adresele IP:

`ntpq --numeric --peers`

- Utilizați `ntpq` în modul de depanare:

`ntpq --debug-level`

- Imprimă valorile variabilelor de sistem NTP:

`ntpq --command={{rv}}`
