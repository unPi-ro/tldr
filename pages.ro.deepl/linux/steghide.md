# steghide

> Instrument de steganografie pentru formatele de fișiere JPEG, BMP, WAV și AU.
> Mai multe informații: <https://github.com/StefanoDeVuono/steghide>.

- Încorporați date într-un PNG, solicitând o frază de acces:

`steghide embed --coverfile {{path/to/image.png}} --embedfile {{path/to/data.txt}}`

- Extrageți date dintr-un fișier audio WAV:

`steghide extract --stegofile {{path/to/sound.wav}}`

- Afișează informații despre fișier, încercând să detecteze un fișier încorporat:

`steghide info {{path/to/file.jpg}}`

- Încorporați date într-o imagine JPEG, utilizând compresia maximă:

`steghide embed --coverfile {{path/to/image.jpg}} --embedfile {{path/to/data.txt}} --compress {{9}}`

- Obțineți lista de algoritmi și moduri de criptare acceptate:

`steghide encinfo`

- Încorporați date criptate într-o imagine JPEG, de exemplu cu Blowfish în modul CBC:

`steghide embed --coverfile {{path/to/image.jpg}} --embedfile {{path/to/data.txt}} --encryption {{blowfish|...}} {{cbc|...}}`
