# http-prompt

> Un client HTTP interactiv de linie de comandă cu autocompletare și evidențiere a sintaxei.
> Mai multe informații: <https://github.com/httpie/http-prompt>.

- Lansarea unei sesiuni care vizează URL-ul implicit al http://localhost:8000 sau sesiunea anterioară:

`http-prompt`

- Lansarea unei sesiuni cu o adresă URL dată:

`http-prompt {{http://example.com}}`

- Lansați o sesiune cu câteva opțiuni inițiale:

`http-prompt {{localhost:8000/api}} --auth {{username:password}}`
