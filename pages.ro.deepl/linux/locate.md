# locate

> Găsiți rapid numele fișierelor.
> Mai multe informații: <https://manned.org/locate>.

- Căutați un model în baza de date. Notă: baza de date este recalculată periodic (de obicei săptămânal sau zilnic):

`locate {{pattern}}`

- Caută un fișier după numele său exact (un model care nu conține caractere de globbing este interpretat ca `*pattern*`):

`locate */{{filename}}`

- Recalculați baza de date. Trebuie să faceți acest lucru dacă doriți să găsiți fișierele adăugate recent:

`sudo updatedb`
