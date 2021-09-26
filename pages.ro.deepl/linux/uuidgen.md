# uuidgen

> Generați identificatori unici (UUID).
> A se vedea și `uuid`.
> Mai multe informații: <https://manned.org/uuidgen>.

- Creați un UUIDv4 aleatoriu:

`uuidgen --random`

- Creează un UUIDv1 bazat pe ora curentă:

`uuidgen --time`

- Creează un UUIDv5 al numelui cu un prefix de spațiu de nume specificat:

`uuidgen --sha1 --namespace {{@dns|@url|@oid|@x500}} --name {{object_name}}`
