# fallocate

> Rezervați sau anulați alocarea de spațiu pe disc pentru fișiere.
> Utilitarul alocă spațiu fără a face zero.
> Mai multe informații: <https://manned.org/fallocate>.

- Rezervați un fișier care ocupă 700 MiB de spațiu pe disc:

`fallocate --length {{700M}} {{path/to/file}}`

- Micșorează un fișier deja alocat cu 200 MiB:

`fallocate --collapse-range --length {{200M}} {{path/to/file}}`

- Micșorarea a 20 MB de spațiu după 100 MiB într-un fișier:

`fallocate --collapse-range --offset {{100M}} --length {{20M}} {{path/to/file}}`
