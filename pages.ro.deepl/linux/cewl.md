# cewl

> Instrument de spidering URL pentru a face o listă de cuvinte de spargere din conținutul web.
> Mai multe informații: <https://digi.ninja/projects/cewl.php>.

- Creează un fișier wordlist de la URL-ul dat până la adâncimea de 2 legături:

`cewl --depth {{2}} --write {{path/to/wordlist.txt}} {{url}}`

- Emite o listă de cuvinte alfanumerice din URL-ul dat, cu cuvinte de minimum 5 caractere:

`cewl --with-numbers --min_word_length {{5}} {{url}}`

- Emite o listă de cuvinte de la URL-ul dat în modul de depanare, inclusiv adresele de e-mail:

`cewl --debug --email {{url}}`

- Emite o listă de cuvinte din URL-ul dat, utilizând autentificarea HTTP Basic sau Digest:

`cewl --auth_type {{basic|digest}} --auth_user {{username}} --auth_pass {{password}} {{url}}`

- Emite o listă de cuvinte de la adresa URL dată prin intermediul unui proxy:

`cewl --proxy_host {{host}} --proxy_port {{port}} {{url}}`
