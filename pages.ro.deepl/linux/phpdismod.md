# phpdismod

> Dezactivați extensiile PHP pe sistemele de operare bazate pe Debian.

- Dezactivați extensia JSON pentru fiecare SAPI din fiecare versiune PHP:

`sudo phpdismod {{json}}`

- Dezactivați extensia JSON pentru PHP 7.3 cu cli SAPI:

`sudo phpdismod -v {{7.3}} -s {{cli}} {{json}}`
