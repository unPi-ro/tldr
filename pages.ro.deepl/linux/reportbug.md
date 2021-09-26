# reportbug

> Instrumentul de raportare a erorilor din distribuția Debian.
> Mai multe informații: <https://manpages.debian.org/buster/reportbug/reportbug.1.en.html>.

- Generați un raport de eroare cu privire la un anumit pachet, apoi trimiteți-l prin e-mail:

`reportbug {{package}}`

- Raportați un bug care nu se referă la un pachet specific (problemă generală, infrastructură etc.):

`reportbug other`

- Scrieți raportul de eroare într-un fișier în loc să îl trimiteți prin e-mail:

`reportbug -o {{filename}} {{package}}`
