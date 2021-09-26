# imgp

> Redimensionator și rotitor de imagine în linie de comandă pentru imagini JPEG și PNG.
> Mai multe informații: <https://github.com/jarun/imgp>.

- Conversia imaginilor individuale și/sau a directoarelor întregi care conțin formate de imagine valide:

`imgp -x {{1366x1000}} {{path/to/directory}} {{path/to/file}}`

- Redimensionați o imagine cu 75
și suprascrieți imaginea sursă la o rezoluție țintă:

`imgp -x {{75}} -w {{path/to/file}}`

- Rotiți o imagine cu 90 de grade în sensul acelor de ceasornic:

`imgp -o {{90}} {{path/to/file}}`
