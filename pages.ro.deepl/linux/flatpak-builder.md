# flatpak-builder

> Ajutați la construirea dependențelor aplicației.
> Mai multe informații: <https://docs.flatpak.org/en/latest/flatpak-builder-command-reference.html>.

- Construiți un Flatpak și exportați-l într-un nou depozit:

`flatpak-builder {{path/to/build_directory}} {{path/to/manifest}}`

- Construiește un Flatpak și îl exportă în depozitul specificat:

`flatpak-builder --repo={{repository_name}} {{path/to/build_directory}} {{path/to/manifest}}`

- Construiți un Flatpak și instalați-l local:

`flatpak-builder --install {{path/to/build_directory}} {{path/to/manifest}}`

- Construiește și semnează un Flatpak și îl exportă în depozitul specificat:

`flatpak-builder --gpg-sign={{key_id}} --repo={{repository_name}} {{path/to/manifest}}`

- Rulați un shell în interiorul unei aplicații sandbox fără a o instala:

`flatpak-builder --run {{path/to/build_directory}} {{path/to/manifest}} {{sh}}`
