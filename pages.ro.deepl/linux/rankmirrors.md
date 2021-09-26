# rankmirrors

> Clasificați o listă de oglinzi Pacman în funcție de conexiune și viteza de deschidere.
> Scrie noua listă de oglinzi în stdout.
> Mai multe informații: <https://wiki.archlinux.org/index.php/mirrors>.

- Clasificați o listă în oglindă:

`rankmirrors {{/etc/pacman.d/mirrorlist}}`

- Afișează doar un anumit număr de servere de top:

`rankmirrors -n {{number}} {{/etc/pacman.d/mirrorlist}}`

- Fiți mai explicit atunci când generați lista de oglinzi:

`rankmirrors -v {{/etc/pacman.d/mirrorlist}}`

- Testați numai un anumit URL:

`rankmirrors --url {{url}}`

- Afișează doar timpii de răspuns în loc de o listă oglindă completă:

`rankmirrors --times {{/etc/pacman.d/mirrorlist}}`
