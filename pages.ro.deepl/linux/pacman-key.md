# pacman-key

> Script de înfășurare pentru GnuPG folosit pentru a gestiona brelocul de chei al lui pacman.
> Mai multe informații: <https://man.archlinux.org/man/pacman-key>.

- Inițializează brelocul pacman:

`sudo pacman-key --init`

- Adăugați cheile implicite ArchLinux:

`sudo pacman-key --populate {{archlinux}}`

- Listează cheile din brelocul de chei publice:

`pacman-key --list-keys`

- Se adaugă cheile specificate:

`sudo pacman-key --add {{path/to/keyfile.gpg}}`

- Primirea unei chei de la un server de chei:

`sudo pacman-key --recv-keys "{{uid|name|email}}"`

- Imprimă amprenta digitală a unei anumite chei:

`pacman-key --finger "{{uid|name|email}}"`

- Semnați local o cheie importată:

`sudo pacman-key --lsign-key "{{uid|name|email}}"`

- Îndepărtați o anumită cheie:

`sudo pacman-key --delete "{{uid|name|email}}"`
