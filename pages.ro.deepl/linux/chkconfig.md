# chkconfig

> Gestionați nivelul de execuție al serviciilor pe CentOS 6.
> Mai multe informații: <https://manned.org/chkconfig>.

- Listează serviciile cu runlevel:

`chkconfig --list`

- Afișează nivelul de execuție al unui serviciu:

`chkconfig --list {{ntpd}}`

- Activează serviciul la pornire:

`chkconfig {{sshd}} on`

- Activați serviciul la pornire pentru nivelurile de execuție 2, 3, 4 și 5:

`chkconfig --level {{2345}} {{sshd}} on`

- Dezactivarea serviciului la pornire:

`chkconfig {{ntpd}} off`

- Dezactivează serviciul la pornire pentru nivelul de execuție 3:

`chkconfig --level {{3}} {{ntpd}} off`
