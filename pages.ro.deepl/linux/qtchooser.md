# qtchooser

> Un wrapper folosit pentru a selecta între versiunile binare de dezvoltare Qt.
> Mai multe informații: <https://manned.org/qtchooser>.

- Listează versiunile Qt disponibile din fișierele de configurare:

`qtchooser --list-versions`

- Imprimă informații despre mediu:

`qtchooser --print-env`

- Rulează instrumentul specificat utilizând versiunea Qt specificată:

`qtchooser --run-tool={{tool}} --qt={{version_name}}`

- Adăugați o intrare pentru versiunea Qt din care să puteți alege:

`qtchooser --install {{version_name}} {{path/to/qmake}}`

- Afișează toate opțiunile disponibile:

`qtchooser --help`
