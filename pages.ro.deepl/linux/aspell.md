# aspell

> Verificator ortografic interactiv.
> Mai multe informații: <http://aspell.net/>.

- Verificarea ortografică a unui singur fișier:

`aspell check {{path/to/file}}`

- Lista cuvintelor scrise greșit de la intrarea standard:

`cat {{file}} | aspell list`

- Afișați limbile disponibile în dicționar:

`aspell dicts`

- Rulați aspell cu o limbă diferită (necesită un cod de limbă ISO 639 din două litere):

`aspell --lang={{cs}}`

- Enumeră cuvintele scrise greșit de la intrarea standard și ignoră cuvintele din lista personală de cuvinte:

`cat {{file}} | aspell --personal={{personal-word-list.pws}} {{list}}`
