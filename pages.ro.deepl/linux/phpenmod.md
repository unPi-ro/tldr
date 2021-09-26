# phpenmod

> Activați extensiile PHP pe sistemele de operare bazate pe Debian.

- Activați extensia JSON pentru fiecare SAPI din fiecare versiune PHP:

`sudo phpenmod {{json}}`

- Activați extensia JSON pentru PHP 7.3 cu cli SAPI:

`sudo phpenmod -v {{7.3}} -s {{cli}} {{json}}`
