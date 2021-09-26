# asciiart

> Conversia imaginilor în ASCII.
> Mai multe informații: <https://github.com/nodanaonlyzuul/asciiart>.

- Citiți o imagine dintr-un fișier și imprimați-o în format ASCII:

`asciiart {{path/to/image.jpg}}`

- Citește o imagine de la un URL și o imprimă în format ASCII:

`asciiart {{www.example.com/image.jpg}}`

- Alegeți lățimea de ieșire (valoarea implicită este 100):

`asciiart -width {{50}} {{path/to/image.jpg}}`

- Colorează ieșirea ASCII:

`asciiart --color {{path/to/image.jpg}}`

- Alegeți formatul de ieșire (formatul implicit este text):

`asciiart --format {{text|html}} {{path/to/image.jpg}}`

- Inversează harta caracterelor:

`asciiart --invert-chars {{path/to/image.jpg}}`
