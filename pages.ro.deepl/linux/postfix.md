# postfix

> Programul de control al agentului de transfer de corespondență Postfix (MTA).
> Vezi și `dovecot`, un agent de livrare a corespondenței (MDA) care se integrează cu Postfix.
> Mai multe informații: <http://www.postfix.org>.

- Verificați configurația:

`sudo postfix check`

- Verificați starea daemonului Postfix:

`sudo postfix status`

- Porniți Postfix:

`sudo postfix start`

- Opriți în mod grațios Postfix:

`sudo postfix stop`

- Golirea cozii de corespondență:

`sudo postfix flush`

- Reîncărcați fișierele de configurare:

`sudo postfix reload`
