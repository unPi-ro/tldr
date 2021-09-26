# po4a-translate

> Conversia unui fișier PO înapoi în format documentație.
> Fișierul PO furnizat ar trebui să fie traducerea fișierului POT care a fost produs de `po4a-gettextize`.
> Mai multe informații: <https://po4a.org/man/man1/po4a-translate.1.php>.

- Conversia unui fișier PO tradus înapoi într-un document:

`po4a-translate --format {{text}} --master {{path/to/master.doc}} --po {{path/to/result.po}} --localized {{path/to/translated.txt}}`

- Obțineți o listă a formatelor disponibile:

`po4a-translate --help-format`
