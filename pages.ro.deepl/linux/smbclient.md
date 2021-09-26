# smbclient

> Client de tip FTP pentru accesarea resurselor SMB/CIFS de pe servere.

- Conectează-te la un share (utilizatorului i se va cere parola; `exit` pentru a ieși din sesiune):

`smbclient {{//server/share}}`

- Conectați-vă cu un alt nume de utilizator:

`smbclient {{//server/share}} --user {{username}}`

- Conectați-vă cu un alt grup de lucru:

`smbclient {{//server/share}} --workgroup {{domain}} --user {{username}}`

- Conectați-vă cu un nume de utilizator și o parolă:

`smbclient {{//server/share}} --user {{username%password}}`

- Descărcați un fișier de pe server:

`smbclient {{//server/share}} --directory {{path/to/directory}} --command "get {{file.txt}}"`

- Încărcați un fișier pe server:

`smbclient {{//server/share}} --directory {{path/to/directory}} --command "put {{file.txt}}"`
