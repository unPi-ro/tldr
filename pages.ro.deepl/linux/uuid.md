# uuid

> Generarea și decodificarea identificatorilor unici universali (UUID).
> Vezi, prin urmare, `uuidgen`.
> Mai multe informații: <https://manned.org/uuid>.

- Generați un UUIDv1 (pe baza orei și a adresei hardware a sistemului, dacă este prezentă):

`uuid`

- Generați un UUIDv4 (pe baza datelor aleatorii):

`uuid -v {{4}}`

- Generați mai mulți identificatori UUIDv4 deodată:

`uuid -v {{4}} -n {{number_of_uuids}}`

- Generează un UUIDv4 și specifică formatul de ieșire:

`uuid -v {{4}} -F {{BIN|STR|SIV}}`

- Generarea unui UUIDv4 și scrierea rezultatului într-un fișier:

`uuid -v {{4}} -o {{path/to/file}}`

- Generează un UUIDv5 (pe baza numelui obiectului furnizat) cu un prefix de spațiu de nume specificat:

`uuid -v {{5}} ns:{{DNS|URL|OID|X500}} {{object_name}}`

- Decodifică un UUID dat:

`uuid -d {{uuid}}`
