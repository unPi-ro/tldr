# xdg-mime

> Consultați și gestionați tipurile MIME în conformitate cu standardul XDG.
> Mai multe informații: <https://portland.freedesktop.org/doc/xdg-mime.html>.

- Afișează tipul MIME al unui fișier:

`xdg-mime query filetype {{path/to/file}}`

- Afișează aplicația implicită pentru deschiderea PNG-urilor:

`xdg-mime query default {{image/png}}`

- Afișează aplicația implicită pentru deschiderea unui anumit fișier:

`xdg-mime query default $(xdg-mime query filetype {{path/to/file}})`

- Setați imv ca aplicație implicită pentru deschiderea imaginilor PNG și JPEG:

`xdg-mime default {{imv.desktop}} {{image/png}} {{image/jpeg}}`
