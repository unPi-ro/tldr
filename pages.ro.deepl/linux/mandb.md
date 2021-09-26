# mandb

> Gestionați baza de date preformatată a paginilor de manual.
> Mai multe informații: <https://man7.org/linux/man-pages/man8/mandb.8.html>.

- Epurarea și procesarea paginilor manuale:

`mandb`

- Actualizarea unei singure intrări:

`mandb --filename {{path/to/file}}`

- Creați intrări de la zero în loc să le actualizați:

`mandb --create`

- Procesează numai bazele de date ale utilizatorilor:

`mandb --user-db`

- Nu curățați intrările învechite:

`mandb --no-purge`

- Verificați valabilitatea paginilor de manual:

`mandb --test`
