# flatpak

> Construiți, instalați și rulați aplicații și runtime-uri flatpak.
> Mai multe informații: <https://docs.flatpak.org/en/latest/flatpak-command-reference.html#flatpak>.

- Rulați o aplicație instalată:

`flatpak run {{name}}`

- Instalați o aplicație de la o sursă la distanță:

`flatpak install {{remote}} {{name}}`

- Enumeră toate aplicațiile și timpii de execuție instalați:

`flatpak list`

- Actualizați toate aplicațiile și timpii de execuție instalați:

`flatpak update`

- Adăugați o sursă la distanță:

`flatpak remote-add --if-not-exists {{remote_name}} {{remote_url}}`

- Listează toate sursele la distanță configurate:

`flatpak remote-list`

- Îndepărtați o aplicație instalată:

`flatpak remove {{name}}`

- Afișează informații despre o aplicație instalată:

`flatpak info {{name}}`
