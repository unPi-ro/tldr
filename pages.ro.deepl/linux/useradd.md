# useradd

> Creați un nou utilizator.
> Mai multe informații: <https://manned.org/useradd>.

- Creați un nou utilizator:

`useradd {{name}}`

- Creați un nou utilizator cu un director principal implicit:

`useradd --create-home {{name}}`

- Creează un nou utilizator cu shell-ul specificat:

`useradd --shell {{path/to/shell}} {{name}}`

- Creați un nou utilizator aparținând unor grupuri suplimentare (atenție la lipsa spațiilor albe):

`useradd --groups {{group1,group2}} {{name}}`

- Creați un nou utilizator de sistem fără un director personal:

`useradd --no-create-home --system {{name}}`
