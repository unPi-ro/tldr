# winetricks

> Gestionați mediile virtuale Windows Wine.
> Mai multe informații: <https://wiki.winehq.org/Winetricks>.

- Porniți o configurare grafică în locația implicită a vinului:

`winetricks`

- Specificați un director Wine personalizat în care să rulați Winetricks:

`WINEPREFIX={{path/to/wine_directory}} winetricks`

- Instalați o DLL sau o componentă Windows în directorul implicit Wine:

`winetricks {{package}}`
