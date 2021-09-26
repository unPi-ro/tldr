# po4a-gettextize

> Conversia unui fișier în fișier PO.
> Mai multe informații: <https://po4a.org/man/man1/po4a-gettextize.1.php>.

- Conversia unui fișier text în fișier PO:

`po4a-gettextize --format {{text}} --master {{path/to/master.txt}} --po {{path/to/result.po}}`

- Obțineți o listă a formatelor disponibile:

`po4a-gettextize --help-format`

- Convertește un fișier text împreună cu un document tradus într-un fișier PO (opțiunea `-l` poate fi furnizată de mai multe ori):

`po4a-gettextize --format {{text}} --master {{path/to/master.txt}} --localized {{path/to/translated.txt}} --po {{path/to/result.po}}`
