# dnf

> Utilitar de gestionare a pachetelor pentru RHEL, Fedora și CentOS (înlocuiește yum).
> Mai multe informații: <https://dnf.readthedocs.io/>.

- Actualizați pachetele instalate la cele mai noi versiuni disponibile:

`sudo dnf upgrade`

- Căutați pachetele prin cuvinte cheie:

`dnf search {{keywords}}`

- Afișează detalii despre un pachet:

`dnf info {{package}}`

- Instalați un nou pachet:

`sudo dnf install {{package}}`

- Instalați un nou pachet și presupuneți că ați răspuns afirmativ la toate întrebările:

`sudo dnf -y install {{package}}`

- Îndepărtați un pachet:

`sudo dnf remove {{package}}`

- Lista pachetelor instalate:

`dnf list --installed`

- Găsește ce pachete furnizează un anumit fișier:

`dnf provides {{file}}`
