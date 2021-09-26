# run-mailcap

> Run MailCap Programs.
> Run mailcap view, see, edit, compose, print - programele de execuție prin intermediul intrărilor din fișierul mailcap (sau oricare dintre aliasurile sale) vor utiliza acțiunea dată pentru a procesa fiecare tip de mime/fișier.

- Acțiunile/programele individuale de pe run-mailcap pot fi invocate cu ajutorul steagului de acțiune:

`run-mailcap --action=ACTION [--option[=value]]`

- Într-un limbaj simplu:

`run-mailcap --action=ACTION {{filename}}`

- Activați informațiile suplimentare:

`run-mailcap --action=ACTION --debug {{filename}}`

- Ignoră orice directivă "copiousoutput" și redirecționează ieșirea către ieșirea standard:

`run-mailcap --action=ACTION --nopager {{filename}}`

- Afișează comanda găsită fără a o executa efectiv:

`run-mailcap --action=ACTION --norun {{filename}}`
