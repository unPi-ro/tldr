# inotifywait

> Așteaptă modificări la unul sau mai multe fișiere.
> Mai multe informații: <https://manned.org/inotifywait>.

- Executați o comandă atunci când se modifică un fișier:

`while inotifywait {{path/to/file}}; do {{command}}; done`

- Fiți liniștiți în ceea ce privește urmărirea schimbărilor:

`while inotifywait --quiet {{path/to/file}}; do {{command}}; done`

- Urmăriți un director în mod recursiv pentru modificări:

`while inotifywait --recursive {{path/to/directory}}; do {{command}}; done`

- Excludeți fișierele care corespund unei expresii regulate:

`while inotifywait --recursive {{path/to/directory}} --exclude '{{regular_expression}}'; do {{command}}; done`

- Așteptați cel mult 30 de secunde:

`while inotifywait --timeout {{30}} {{path/to/file}}; do {{command}}; done`

- Urmăriți numai evenimentele de modificare a fișierelor:

`while inotifywait --event {{modify}} {{path/to/file}}; do {{command}}; done`
