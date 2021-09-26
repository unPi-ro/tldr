# xcursorgen

> Creați un fișier cursor X dintr-o colecție de PNG-uri.
> Dacă `--prefix` este omis, fișierele imagine trebuie să fie localizate în directorul de lucru curent.
> Mai multe informații: <https://manned.org/xcursorgen.1>.

- Creați un fișier cursor X utilizând un fișier de configurare:

`xcursorgen {{path/to/config.cursor}} {{path/to/output_file}}`

- Creați un fișier cursor X utilizând un fișier de configurare și specificați calea către fișierele imagine:

`xcursorgen --prefix {{path/to/image_directory/}} {{path/to/config.cursor}} {{path/to/output_file}}`

- Creați un fișier cursor X utilizând un fișier de configurare și scrieți ieșirea în stdout:

`xcursorgen {{path/to/config.cursor}}`
