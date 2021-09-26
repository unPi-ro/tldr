# dex

> DesktopEntry Execution e un program pentru a genera și executa fișiere DesktopEntry de tip Application.
> Mai multe informații: <https://github.com/jceb/dex>.

- Executați toate programele din dosarele de pornire automată:

`dex --autostart`

- Execută toate programele din dosarele specificate:

`dex --autostart --search-paths {{path/to/directory1}}:{{path/to/directory2}}:{{path/to/directory3}}:`

- Previzualizarea programelor va fi executată într-un autostart specific GNOME:

`dex --autostart --environment {{GNOME}}`

- Previzualizarea programelor va fi executată în cadrul unei porniri automate obișnuite:

`dex --autostart --dry-run`

- Previzualizează valoarea proprietății DesktopEntry `Name`:

`dex --property {{Name}} {{path/to/file.desktop}}`

- Creează un DesktopEntry pentru un program din directorul curent:

`dex --create {{path/to/file.desktop}}`

- Execută un singur program (cu `Terminal=true` în fișierul desktop) în terminalul dat:

`dex --term {{terminal}} {{path/to/file.desktop}}`
