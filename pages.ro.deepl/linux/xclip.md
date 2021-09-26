# xclip

> Instrument de manipulare a clipboard-ului X11, similar cu `xsel`.
> Gestionează selecțiile primare și secundare X, plus clipboard-ul sistemului (`Ctrl C`/`Ctrl V`).

- Copiază rezultatul unei comenzi în zona de selecție primară X11 (clipboard):

`echo 123 | xclip`

- Copiază rezultatul unei comenzi într-o anumită zonă de selecție X11:

`echo 123 | xclip -selection {{primary|secondary|clipboard}}`

- Copiază rezultatul unei comenzi în clipboardul sistemului, folosind notația scurtă:

`echo 123 | xclip -sel clip`

- Copiați conținutul unui fișier în clipboard-ul sistemului:

`xclip -sel clip {{input_file.txt}}`

- Copiați conținutul unui PNG în clipboard-ul sistemului (poate fi lipit corect în alte programe):

`xclip -sel clip -t image/png {{input_file.png}}`

- Copiați datele introduse de utilizator în consolă în clipboardul sistemului:

`xclip -i`

- Lipiți conținutul zonei de selecție primară X11 în consolă:

`xclip -o`

- Lipiți conținutul clipboard-ului sistemului în consolă:

`xclip -o -sel clip`
