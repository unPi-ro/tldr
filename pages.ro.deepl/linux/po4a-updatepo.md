# po4a-updatepo

> Actualizarea traducerii (în format PO) a unei documentații.
> Mai multe informații: <https://po4a.org/man/man1/po4a-updatepo.1.php>.

- Actualizarea unui fișier PO în funcție de modificarea fișierului său de origine:

`po4a-updatepo --format {{text}} --master {{path/to/master.txt}} --po {{path/to/result.po}}`

- Obțineți o listă a formatelor disponibile:

`po4a-updatepo --help-format`

- Actualizarea mai multor fișiere PO în funcție de modificarea fișierului lor de origine:

`po4a-updatepo --format {{text}} --master {{path/to/master.txt}} --po {{path/to/po1.po}} --po {{path/to/po2.po}}`
