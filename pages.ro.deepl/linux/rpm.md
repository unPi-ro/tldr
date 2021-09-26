# rpm

> RPM Package Manager.

- Afișează versiunea pachetului httpd:

`rpm -q {{httpd}}`

- Listează versiunile tuturor pachetelor corespunzătoare:

`rpm -qa '{{mariadb*}}'`

- Instalarea forțată a unui pachet, indiferent de versiunile instalate în prezent:

`rpm -U {{package_name.rpm}} --force`

- Identificarea proprietarului unui fișier și afișarea versiunii pachetului:

`rpm -qf {{/etc/postfix/main.cf}}`

- Listează fișierele deținute de pachet:

`rpm -ql {{kernel}}`

- Afișează scripturile dintr-un fișier RPM:

`rpm -qp --scripts {{package_name.rpm}}`

- Afișează fișierele modificate, lipsă și/sau instalate incorect din pachetele corespunzătoare:

`rpm -Va '{{php-*}}'`
