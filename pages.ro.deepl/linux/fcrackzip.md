# fcrackzip

> ZIP arhivă arhivă parolă de cracare utilitar.
> Mai multe informații: <https://manned.org/fcrackzip>.

- Forțați o parolă cu o lungime de 4 până la 8 caractere și care conține numai caractere alfanumerice (ordinea contează):

`fcrackzip --brute-force --length 4-8 --charset aA1 {{archive}}`

- Brute-force o parolă în modul verbose cu o lungime de 3 caractere care conține numai caractere minuscule, `$` și `%`:

`fcrackzip -v --brute-force --length 3 --charset a:$% {{archive}}`

- Forțați o parolă care să conțină numai caractere minuscule și speciale:

`fcrackzip --brute-force --length 4 --charset a! {{archive}}`

- Brute-force o parolă care conține numai cifre, începând cu parola `12345`:

`fcrackzip --brute-force --length 5 --charset 1 --init-password 12345 {{archive}}`

- Spargeți o parolă folosind o listă de cuvinte:

`fcrackzip --use-unzip --dictionary --init-password {{wordlist}} {{archive}}`

- Performanțe de referință în materie de cracare:

`fcrackzip --benchmark`
