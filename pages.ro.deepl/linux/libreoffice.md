# libreoffice

> CLI pentru puternica suită office gratuită LibreOffice.
> Mai multe informații: <https://www.libreoffice.org/>.

- Deschide o listă de fișiere separate prin spații în modul doar pentru citire:

`libreoffice --view {{path/to/file1}} {{path/to/file2}}`

- Afișarea conținutului anumitor fișiere:

`libreoffice --cat {{path/to/file1}} {{path/to/file2}}`

- Tipăriți fișiere la o anumită imprimantă:

`libreoffice --pt {{printer_name}} {{path/to/file1}} {{path/to/file2}}`

- Convertește toate fișierele `.doc` din directorul curent în PDF:

`libreoffice --convert-to {{pdf}} {{*.doc}}`
