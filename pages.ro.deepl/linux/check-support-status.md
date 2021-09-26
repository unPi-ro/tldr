# check-support-status

> Identificați pachetele Debian instalate pentru care suportul a trebuit să fie limitat sau s-a încheiat prematur.
> Mai multe informații: <https://manpages.debian.org/buster/debian-security-support/check-support-status.1.en.html>.

- Afișarea pachetelor al căror suport este limitat, s-a încheiat deja sau se va încheia mai devreme de sfârșitul duratei de viață a distribuției:

`check-support-status`

- Afișează numai pachetele al căror suport s-a încheiat:

`check-support-status --type {{ended}}`

- Treceți peste tipărirea unui titlu:

`check-support-status --no-heading`
