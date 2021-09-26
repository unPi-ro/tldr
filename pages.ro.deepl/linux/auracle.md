# auracle

> Instrument de linie de comandă utilizat pentru a interacționa cu depozitul de utilizatori Arch Linux, denumit în mod obișnuit AUR.
> Mai multe informații: <https://github.com/falconindy/auracle>.

- Afișează pachetele AUR care se potrivesc cu o expresie regulată:

`auracle search '{{regular_expression}}'`

- Afișează informații despre pachete pentru o listă de pachete AUR separate prin spații:

`auracle info {{package1}} {{package2}}`

- Afișează fișierul `PKGBUILD` (informații despre compilare) pentru o listă de pachete AUR separate prin spațiu:

`auracle show {{package1}} {{package2}}`

- Afișează actualizările pentru pachetele AUR instalate:

`auracle outdated`
