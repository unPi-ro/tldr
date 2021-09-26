# kwriteconfig5

> Scrieți intrările KConfig pentru KDE Plasma.
> Mai multe informații: <https://userbase.kde.org/KDE_System_Administration/Configuration_Files>.

- Ajutor pentru afișare:

`kwriteconfig5 --help`

- Setați o cheie de configurare globală:

`kwriteconfig5 --group {{group_name}} --key {{key}} {{value}}`

- Setați o cheie într-un anumit fișier de configurare:

`kwriteconfig5 --file {{path/to/file}} --group {{group_name}} --key {{key}} {{value}}`

- Ștergeți o tastă:

`kwriteconfig5 --group {{group_name}} --key {{key}} --delete`

- Utilizați systemd pentru a porni sesiunea Plasma atunci când este disponibilă:

`kwriteconfig5 --file {{startkderc}} --group {{General}} --key {{systemdBoot}} {{true}}`

- Ascundeți bara de titlu atunci când o fereastră este maximizată (ca în Ubuntu):

`kwriteconfig5 --file {{~/.config/kwinrc}} --group {{Windows}} --key {{BorderlessMaximizedWindows}} {{true}}`

- Configurați KRunner pentru a se deschide cu tasta rapidă globală Meta (Command/Windows):

`kwriteconfig5 --file {{~/.config/kwinrc}} --group {{ModifierOnlyShortcuts}} --key {{Meta}} {{"org.kde.kglobalaccel,/component/krunner_desktop,org.kde.kglobalaccel.Component,invokeShortcut,_launch"}}`
