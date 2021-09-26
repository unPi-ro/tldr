# kreadconfig5

> Citiți intrările KConfig pentru KDE Plasma.
> Mai multe informații: <https://userbase.kde.org/KDE_System_Administration/Configuration_Files>.

- Citește o cheie din configurația globală:

`kreadconfig5 --group {{group_name}} --key {{key_name}}`

- Citește o cheie dintr-un anumit fișier de configurare:

`kwriteconfig5 --file {{path/to/file}} --group {{group_name}} --key {{key_name}}`

- Verificați dacă systemd este utilizat pentru a porni sesiunea Plasma:

`kreadconfig5 --file {{startkderc}} --group {{General}} --key {{systemdBoot}}`
