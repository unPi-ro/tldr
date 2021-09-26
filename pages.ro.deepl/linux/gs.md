# gs

> GhostScript este un interpretor PDF și PostScript.
> Mai multe informații: <https://manned.org/gs>.

- Pentru a vizualiza un fișier:

`gs -dQUIET -dBATCH {{file.pdf}}`

- Reduceți dimensiunea fișierului PDF la imagini de 150 dpi pentru citirea pe un dispozitiv e-book:

`gs -dNOPAUSE -dQUIET -dBATCH -sDEVICE=pdfwrite -dPDFSETTINGS=/ebook -sOutputFile={{output.pdf}} {{input.pdf}}`

- Convertiți fișierul PDF (paginile 1 - 3) într-o imagine cu o rezoluție de 150 dpi:

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=jpeg -r150 -dFirstPage={{1}} -dLastPage={{3}} -sOutputFile={{output_%d.jpg}} {{input.pdf}}`

- Extrageți pagini dintr-un fișier PDF:

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile={{output.pdf}} {{input.pdf}}`

- Îmbinarea fișierelor PDF:

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile={{output.pdf}} {{input1.pdf}} {{input2.pdf}}`

- Conversia unui fișier PostScript în fișier PDF:

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile={{output.pdf}} {{input.ps}}`
