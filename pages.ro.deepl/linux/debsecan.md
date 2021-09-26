# debsecan

> Debian Security Analyzer, un instrument care listează vulnerabilitățile unei anumite instalări Debian.
> Mai multe informații: <https://gitlab.com/fweimer/debsecan>.

- Lista pachetelor vulnerabile instalate pe gazda curentă:

`debsecan`

- Lista pachetelor vulnerabile instalate dintr-o anumită suită:

`debsecan --suite {{release_code_name}}`

- Enumerați numai vulnerabilitățile rezolvate:

`debsecan --suite {{release_code_name}} --only-fixed`

- Enumerați numai vulnerabilitățile corectate din unstable ("sid") și trimiteți un e-mail către root:

`debsecan --suite {{sid}} --only-fixed --format {{report}} --mailto {{root}} --update-history`

- Actualizați pachetele instalate vulnerabile:

`sudo apt upgrade $(debsecan --only-fixed --format {{packages}})`
