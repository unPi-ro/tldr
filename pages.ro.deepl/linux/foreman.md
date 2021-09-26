# foreman

> Gestionați aplicațiile bazate pe Procfile.
> Mai multe informații: <https://manned.org/foreman>.

- Pornește o aplicație cu fișierul Procfile din directorul curent:

`foreman start`

- Pornește o aplicație cu un fișier Procfile specificat:

`foreman start -f {{Procfile}}`

- Porniți o aplicație specifică:

`foreman start {{process}}`

- Validarea formatului Procfile:

`foreman check`

- Executați comenzi unice cu mediul procesului:

`foreman run {{command}}`

- Porniți toate procesele, cu excepția celui numit "worker":

`foreman start -m all=1,{{worker}}=0`
