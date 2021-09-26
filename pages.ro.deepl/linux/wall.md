# wall

> Scrieți un mesaj pe terminalele utilizatorilor conectați în prezent.

- Trimiteți un mesaj:

`echo "{{message}}" | wall`

- Trimiteți un mesaj dintr-un fișier:

`wall {{file}}`

- Trimite un mesaj cu timeout (implicit 300):

`wall -t {{seconds}} {{file}}`
