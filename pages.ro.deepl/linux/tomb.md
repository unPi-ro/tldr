# tomb

> Gestionați directoare de stocare criptate care pot fi transportate și ascunse în siguranță într-un sistem de fișiere.
> Mai multe informații: <https://www.dyne.org/software/tomb/>.

- Creați un nou mormânt cu o dimensiune inițială de 100 MB:

`tomb dig -s {{100}} {{encrypted_directory.tomb}}`

- Creați un nou fișier cheie care poate fi utilizat pentru a bloca un mormânt; utilizatorului i se va solicita o parolă pentru cheie:

`tomb forge {{encrypted_directory.tomb.key}}`

- Crearea forțată a unei chei noi, chiar dacă mormântul nu permite falsificarea cheilor (din cauza schimbului):

`tomb forge {{encrypted_directory.tomb.key}} -f`

- Inițializează și blochează un mormânt gol folosind o cheie făcută cu `forge`:

`tomb lock {{encrypted_directory.tomb}} -k {{encrypted_directory.tomb.key}}`

- Montează un mormânt (în mod implicit în `/media`) folosind cheia acestuia, făcându-l utilizabil ca un director obișnuit al sistemului de fișiere:

`tomb open {{encrypted_directory.tomb}} -k {{encrypted_directory.tomb.key}}`

- Închide un mormânt (eșuează dacă mormântul este utilizat de un proces):

`tomb close {{encrypted_directory.tomb}}`

- Închideți cu forța toate mormintele deschise, omorând toate aplicațiile care le folosesc:

`tomb slam all`

- Lista tuturor mormintelor deschise:

`tomb list`
