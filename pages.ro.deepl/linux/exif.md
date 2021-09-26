# exif

> Afișați și modificați informațiile EXIF din fișierele JPEG.
> Mai multe informații: <https://github.com/libexif/exif/>.

- Afișează toate informațiile EXIF recunoscute într-o imagine:

`exif {{path/to/image.jpg}}`

- Afișează un tabel care enumeră etichetele EXIF cunoscute și indică dacă fiecare dintre ele există într-o imagine:

`exif --list-tags --no-fixup {{image.jpg}}`

- Extrageți miniatura imaginii în fișierul `thumbnail.jpg`:

`exif --extract-thumbnail --output={{thumbnail.jpg}} {{image.jpg}}`

- Afișează conținutul brut al etichetei "Model" din imaginea dată:

`exif --ifd={{0}} --tag={{Model}} --machine-readable {{image.jpg}}`

- Schimbați valoarea etichetei "Artist" în John Smith și salvați-o în `new.jpg`:

`exif --output={{new.jpg}} --ifd={{0}} --tag="{{Artist}}" --set-value="{{John Smith}}" --no-fixup {{image.jpg}}`
