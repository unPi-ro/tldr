# phar

> Creați, actualizați sau extrageți arhive PHP (PHAR).

- Adăugați fișiere sau directoare separate prin spații la un fișier Phar:

`phar add -f {{path/to/phar_file}} {{files_or_directories}}`

- Afișează conținutul unui fișier Phar:

`phar list -f {{path/to/phar_file}}`

- Șterge fișierul sau directorul specificat dintr-un fișier Phar:

`phar delete -f {{path/to/phar_file}} -e {{file_or_directory}}`

- Afișează informații complete de utilizare și algoritmi de hashing/compresie disponibili:

`phar help`

- Comprimați sau decomprimați fișierele și directoarele dintr-un fișier Phar:

`phar compress -f {{path/to/phar_file}} -c {{algorithm}}`

- Obține informații despre un fișier Phar:

`phar info -f {{path/to/phar_file}}`

- Semnează un fișier Phar cu un anumit algoritm hash:

`phar sign -f {{path/to/phar_file}} -h {{algorithm}}`

- Semnează un fișier Phar cu o cheie privată OpenSSL:

`phar sign -f {{path/to/phar_file}} -h openssl -y {{path/to/private_key}}`
