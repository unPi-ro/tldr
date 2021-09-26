# apache2ctl

> Instrumentul CLI pentru administrarea serverului web HTTP Apache.
> Această comandă vine cu sistemele de operare bazate pe Debian, pentru cele bazate pe RHEL vezi `httpd`.
> Mai multe informații: <https://manpages.debian.org/latest/apache2/apache2ctl.8.en.html>.

- Porniți demonul Apache. Aruncă un mesaj dacă acesta este deja în funcțiune:

`sudo apache2ctl start`

- Opriți demonul Apache:

`sudo apache2ctl stop`

- Reporniți demonul Apache:

`sudo apache2ctl restart`

- Testează sintaxa fișierului de configurare:

`sudo apache2ctl -t`

- Lista modulelor încărcate:

`sudo apache2ctl -M`
