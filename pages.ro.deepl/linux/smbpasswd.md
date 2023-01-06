# smbpasswd

> Schimbați parola SMB a unui utilizator.
> Utilizatorii Samba trebuie să aibă, de asemenea, un cont Unix local.

- Modificați parola SMB a utilizatorului curent:

`smbpasswd`

- Adăugați un utilizator specificat la Samba și setați parola (utilizatorul trebuie să existe deja în sistem):

`smbpasswd -a {{username}}`

- Modificați parola unui utilizator Samba existent:

`smbpasswd {{username}}`

- Ștergeți un utilizator Samba:

`smbpasswd -x {{username}}`