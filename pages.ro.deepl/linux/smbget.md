# smbget

> Utilitar de tip `wget` pentru descărcarea fișierelor de pe serverele SMB.
> Mai multe informații: <https://www.samba.org/samba/docs/current/man-html/smbget.1.html>.

- Descărcați un fișier de pe un server:

`smbget {{smb://server/share/file}}`

- Descărcați un share sau un director în mod recursiv:

`smbget --recursive {{smb://server/share}}`

- Conectați-vă cu un nume de utilizator și o parolă:

`smbget {{smb://server/share/file}} --user {{username%password}}`

- Solicitați transferuri criptate:

`smbget {{smb://server/share/file}} --encrypt`
