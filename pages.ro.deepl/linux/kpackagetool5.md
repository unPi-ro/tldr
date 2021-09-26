# kpackagetool5

> KPackage Manager: Instalarea, listarea și eliminarea pachetelor Plasma.
> Mai multe informații: <https://techbase.kde.org/Development/Tutorials/Plasma5/QML2/GettingStarted#Kpackagetool5>.

- Enumeră toate tipurile de pachete cunoscute care pot fi instalate:

`kpackagetool5 --list-types`

- Instalați pachetul dintr-un director:

`kpackagetool5 --type {{package_type}} --install {{path/to/directory}}`

- Actualizarea pachetului instalat dintr-un director:

`kpackagetool5 --type {{package_type}} --upgrade {{path/to/directory}}`

- Listează plasmoidele instalate (--global pentru toți utilizatorii):

`kpackagetool5 --type Plasma/Applet --list --global`

- Îndepărtați un plasmoid după nume:

`kpackagetool5 --type Plasma/Applet --remove "{{name}}"`
