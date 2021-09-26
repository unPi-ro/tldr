# a2query

> Recuperați configurația de execuție de la Apache pe sistemele de operare bazate pe Debian.
> Mai multe informații: <https://manpages.debian.org/buster/apache2/a2query.1.en.html>.

- Lista modulelor Apache activate:

`sudo a2query -m`

- Verifică dacă un anumit modul este instalat:

`sudo a2query -m {{module_name}}`

- Lista gazdelor virtuale activate:

`sudo a2query -s`

- Afișează modulul de procesare multiplă activat în prezent:

`sudo a2query -M`

- Afișează versiunea Apache:

`sudo a2query -v`
