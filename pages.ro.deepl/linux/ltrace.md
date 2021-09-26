# ltrace

> Afișați apelurile de bibliotecă dinamică ale unui proces.
> Mai multe informații: <https://manned.org/ltrace>.

- Imprimă (urmărește) apelurile de bibliotecă ale unui program binar:

`ltrace ./{{program}}`

- Numărați apelurile la bibliotecă. Imprimați un rezumat la îndemână în partea de jos:

`ltrace -c {{path/to/program}}`

- Urmăriți apelurile la malloc și free, omiteți-le pe cele efectuate de libc:

`ltrace -e malloc+free-@libc.so* {{path/to/program}}`

- Scrieți în fișier în loc de terminal:

`ltrace -o {{file}} {{path/to/program}}`
