# zgrep

> Căutați tipare de text din fișiere în interiorul unui fișier comprimat (echivalent cu grep -Z).

- Căutați un model într-un fișier comprimat (sensibil la majuscule și minuscule):

`zgrep {{pattern}} {{path/to/compressed/file}}`

- Căutați un model într-un fișier comprimat (nu ține cont de majuscule și minuscule):

`zgrep -i {{pattern}} {{path/to/compressed/file}}`

- Numărul de linii de ieșire care conțin modelul potrivit într-un fișier comprimat:

`zgrep -c {{pattern}} {{path/to/compressed/file}}`

- Afișează liniile care nu au modelul prezent (inversează funcția de căutare):

`zgrep -v {{pattern}} {{path/to/compressed/file}}`

- Căutați mai multe modele într-un fișier comprimat:

`zgrep -e "{{pattern_1}}" -e "{{pattern_2}}" {{path/to/compressed/file}}`

- Utilizați expresii regulate extinse (care acceptă `?`, ` `, `{}`, `()` și `|`):

`zgrep -E {{regular_expression}} {{path/to/file}}`

- Tipărește 3 rânduri de [C]ontext în jurul, [A]nainte sau [B]ână la fiecare potrivire:

`zgrep -{{C|B|A}} {{3}} {{pattern}} {{path/to/compressed/file}}`
