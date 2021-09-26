# dconf write

> Scrieți o valoare într-o cale a bazei de date dconf.
> Mai multe informații: <https://developer.gnome.org/dconf>.

- Scrie un șir de caractere într-o cale dconf (observați ghilimelele imbricate):

`dconf write {{/example/dconf/path}} "'{{Example Value}}'"`

- Scrie un boolean pe o cale dconf:

`dconf write {{/example/dconf/path}} {{true|false}}`

- Scrie un număr întreg pe o cale dconf:

`dconf write {{/example/dconf/path}} {{16}}`

- Scrie o matrice pe o cale dconf:

`dconf write {{/example/dconf/path}} "[{{'My First Value', 'My Second Value'}}]"`

- Scrie o matrice goală pe o cale dconf:

`dconf write {{/example/dconf/path}} "@as []"`
