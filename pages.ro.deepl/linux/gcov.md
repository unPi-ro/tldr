# gcov

> Instrument de analiză a acoperirii codului și profilare care descoperă părțile netestate ale unui program.
> Afișează, de asemenea, o copie a codului sursă adnotată cu frecvențele de execuție a segmentelor de cod.
> Mai multe informații: <https://gcc.gnu.org/onlinedocs/gcc/Invoking-Gcov.html>.

- Se generează un raport de acoperire numit `file.cpp.gcov`:

`gcov {{path/to/file.cpp}}`

- Scrieți numărul de execuții individuale pentru fiecare bloc de bază:

`gcov --all-blocks {{path/to/file.cpp}}`

- Scrieți frecvențele de ramificare în fișierul de ieșire și imprimați informații sumare în stdout sub formă de procente:

`gcov --branch-probabilities {{path/to/file.cpp}}`

- Scrieți frecvențele de ramificare ca număr de ramificații luate, mai degrabă decât ca procent:

`gcov --branch-counts {{path/to/file.cpp}}`

- Nu creați un fișier de ieșire `gcov`:

`gcov --no-output {{path/to/file.cpp}}`

- Scrieți rezumate la nivel de fișier, precum și la nivel de funcție:

`gcov --function-summaries {{path/to/file.cpp}}`
