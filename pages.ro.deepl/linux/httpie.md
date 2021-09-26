# httpie

> Un instrument HTTP cu linie de comandă ușor de utilizat.
> Mai multe informații: <https://github.com/httpie/httpie>.

- Trimite o cerere GET (metodă implicită fără date de cerere):

`http {{https://example.com}}`

- Trimiteți o cerere POST (metoda implicită cu date de cerere):

`http {{https://example.com}} {{hello=World}}`

- Trimiteți o cerere POST cu date de intrare redirecționate:

`http {{https://example.com}} < {{file.json}}`

- Trimite o cerere PUT cu un corp JSON dat:

`http PUT {{https://example.com/todos/7}} {{hello=world}}`

- Trimite o cerere DELETE cu un antet de cerere dat:

`http DELETE {{https://example.com/todos/7}} {{API-Key:foo}}`

- Afișează întregul schimb HTTP (atât cererea, cât și răspunsul):

`http -v {{https://example.com}}`

- Descărcați un fișier:

`http --download {{https://example.com}}`
