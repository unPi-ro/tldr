# faketime

> Falsifică timpul sistemului pentru o anumită comandă.
> Mai multe informații: <https://manpages.ubuntu.com/manpages/trusty/man1/faketime.1.html>.

- Falsifică ora în această seară, înainte de a imprima rezultatul lui `date`:

`faketime '{{today 23:30}}' {{date}}`

- Deschideți un nou shell `bash`, care folosește ieri ca dată curentă:

`faketime '{{yesterday}}' {{bash}}`

- Simulați cum ar acționa un program vinerea viitoare:

`faketime '{{next Friday 1 am}}' {{path/to/program}}`
