# arch-chroot

> Comanda `chroot` îmbunătățită pentru a ajuta în procesul de instalare Arch Linux.
> Mai multe informații: <https://man.archlinux.org/man/arch-chroot.8>.

- Pornește un shell interactiv (`bash`, în mod implicit) într-un nou director rădăcină:

`arch-chroot {{path/to/new/root}}`

- Specificați utilizatorul (altul decât utilizatorul curent) cu care se execută shell-ul:

`arch-chroot -u {{user}} {{path/to/new/root}}`

- Rulați o comandă personalizată (în locul comenzii implicite `bash`) în noul director rădăcină:

`arch-chroot {{path/to/new/root}} {{command}} {{command_arguments}}`

- Specificați shell-ul, altul decât cel implicit `bash` (în acest caz, pachetul `zsh` trebuie să fie instalat în sistemul țintă):

`arch-chroot {{path/to/new/root}} {{zsh}}`
