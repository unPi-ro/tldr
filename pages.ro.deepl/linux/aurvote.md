# aurvote

> Votați pentru pachetele din depozitul utilizatorilor Arch.
> Pentru a putea vota, fișierul `~/.config/aurvote` trebuie să existe și să conțină acreditările dumneavoastră AUR.
> Mai multe informații: <https://github.com/archlinuxfr/aurvote>.

- Creați în mod interactiv fișierul `~/.config/aurvote` care conține numele de utilizator și parola dumneavoastră AUR:

`aurvote --configure`

- Votați pentru unul sau mai multe pachete AUR:

`aurvote {{package1 package2 ...}}`

- Dezvotați unul sau mai multe pachete AUR:

`aurvote --unvote {{package1 package2 ...}}`

- Verificați dacă unul sau mai multe pachete AUR au fost deja votate:

`aurvote --check {{package1 package2 ...}}`

- Arată ajutorul pentru `aurvote`:

`aurvote --help`
