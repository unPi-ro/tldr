# jpegtran

> Efectuați transformarea fără pierderi a fișierelor JPEG.
> Mai multe informații: <https://manned.org/jpegtran>.

- Oglindiți o imagine pe orizontală sau pe verticală:

`jpegtran -flip {{horizontal|vertical}} {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Rotiți o imagine cu 90, 180 sau 270 de grade în sensul acelor de ceasornic:

`jpegtran -rotate {{90|180|270}} {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Transpuneți imaginea pe axa din stânga sus spre dreapta jos:

`jpegtran -transpose {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Transversalitatea imaginii pe axa din dreapta sus spre stânga jos:

`jpegtran -transverse {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Conversia imaginii în tonuri de gri:

`jpegtran -grayscale {{path/to/image.jpg}} > {{path/to/output.jpg}}`

- Decuparea imaginii într-o regiune dreptunghiulară cu lățimea `W` și înălțimea `H` din colțul din stânga-sus, salvând rezultatul într-un fișier specific:

`jpegtran -crop {{W}}x{{H}} -outfile {{path/to/output.jpg}} {{path/to/image.jpg}}`

- Se decupează imaginea într-o regiune dreptunghiulară cu lățimea `W` și înălțimea `H`, pornind de la punctele `X` și `Y` din colțul din stânga sus:

`jpegtran -crop {{W}}x{{H}}+{{X}}+{{Y}} {{path/to/image.jpg}} > {{path/to/output.jpg}}`
