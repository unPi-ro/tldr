# runuser

> Executați comenzi ca un anumit utilizator și grup fără a cere parola (necesită privilegii de root).

- Rulați comanda ca un alt utilizator:

`runuser {{user}} -c '{{command}}'`

- Rulați comanda ca utilizator și grup diferit:

`runuser {{user}} -g {{group}} -c '{{command}}'`

- Pornește un shell de autentificare ca un anumit utilizator:

`runuser {{user}} -l`

- Specificați un shell pentru funcționare în locul shell-ului implicit (funcționează și pentru autentificare):

`runuser {{user}} -s {{/bin/sh}}`

- Păstrează întregul mediu al root (numai dacă nu este specificat `--login`):

`runuser {{user}} --preserve-environment -c '{{command}}'`
