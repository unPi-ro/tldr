# csplit

> Împărțiți un fișier în bucăți.
> Acest lucru generează fișiere numite "xx00", "xx01" și așa mai departe.
> Mai multe informații: <https://www.gnu.org/software/coreutils/csplit>.

- Împărțiți un fișier la liniile 5 și 23:

`csplit {{file}} {{5}} {{23}}`

- Împărțiți un fișier la fiecare 5 linii (această operațiune va eșua dacă numărul total de linii nu este divizibil cu 5):

`csplit {{file}} {{5}} {*}`

- Împărțiți un fișier la fiecare 5 linii, ignorând eroarea de divizare exactă:

`csplit -k {{file}} {{5}} {*}`

- Împărțiți un fișier la linia 5 și utilizați un prefix personalizat pentru fișierele de ieșire:

`csplit {{file}} {{5}} -f {{prefix}}`

- Împarte un fișier la o linie care corespunde unei expresii regulate:

`csplit {{file}} /{{regular_expression}}/`
