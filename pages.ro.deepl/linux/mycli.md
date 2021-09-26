# mycli

> Un CLI pentru MySQL, MariaDB și Percona cu autocompletare și evidențiere a sintaxei.
> Mai multe informații: <https://manned.org/mycli>.

- Se conectează la o bază de date cu utilizatorul conectat în mod curent:

`mycli {{database_name}}`

- Se conectează la o bază de date cu utilizatorul specificat:

`mycli -u {{user}} {{database_name}}`

- Se conectează la o bază de date de pe gazda specificată cu utilizatorul specificat:

`mycli -u {{user}} -h {{host}} {{database_name}}`
