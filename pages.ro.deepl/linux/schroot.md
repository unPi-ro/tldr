# schroot

> Executați comanda sau porniți un shell interactiv cu un alt director rădăcină. Mai ușor de personalizat decât `chroot`.
> Mai multe informații: <https://wiki.debian.org/Schroot>.

- Executați o comandă într-un chroot specific:

`schroot --chroot {{chroot}} {{command}}`

- Rularea unei comenzi cu opțiuni într-un chroot specific:

`schroot --chroot {{chroot}} {{command}} -- {{command_options}}`

- Executați o comandă în toate rădăcinile disponibile:

`schroot --all {{command}}`

- Pornește un shell interactiv în cadrul unui chroot specific ca utilizator specific:

`schroot --chroot {{chroot}} --user {{user}}`

- Enumeră rădăcinile disponibile:

`schroot --list`
