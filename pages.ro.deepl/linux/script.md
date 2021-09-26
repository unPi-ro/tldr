# script

> Înregistrați toate ieșirile terminalului în fișier.

- Înregistrează o nouă sesiune într-un fișier numit `typescript` în directorul curent:

`script`

- Înregistrează o nouă sesiune pe un traseu de fișier personalizat:

`script {{path/to/session.out}}`

- Înregistrează o nouă sesiune, adăugând-o la un fișier existent:

`script -a {{path/to/session.out}}`

- Înregistrarea informațiilor de sincronizare (datele sunt transmise la eroarea standard):

`script -t 2> {{path/to/timingfile}}`
