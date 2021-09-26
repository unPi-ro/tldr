# as

> Asamblorator GNU portabil.
> Destinat în primul rând să asambleze ieșirea din `gcc` pentru a fi folosită de `ld`.
> Mai multe informații: <https://manned.org/as>.

- Asamblează un fișier, scriind rezultatul în `a.out`:

`as {{file.s}}`

- Asamblează rezultatul într-un fișier dat:

`as {{file.s}} -o {{out.o}}`

- Generarea mai rapidă a ieșirii prin omiterea preprocesării spațiilor albe și a comentariilor. (Ar trebui să fie utilizat numai pentru compilatoare de încredere):

`as -f {{file.s}}`

- Include o cale dată în lista de directoare în care se caută fișierele specificate în directivele `.include`:

`as -I {{path/to/directory}} {{file.s}}`
