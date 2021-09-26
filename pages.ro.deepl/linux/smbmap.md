# smbmap

> Instrument de enumerare SMB.
> Mai multe informații: <https://github.com/ShawnDEvans/smbmap>.

- Afișează partajările și permisiunile SMB pe o gazdă, solicitând parola utilizatorului sau hash-ul NTLM:

`smbmap -u {{username}} --prompt -H {{ip}}`

- Afișează partajările și permisiunile SMB pe o gazdă, specificând domeniul și trecând parola NTLM hash:

`smbmap -u {{username}} --prompt -d {{domain}} -H {{ip}}`

- Afișează partajările SMB și listează un singur nivel de directoare și fișiere:

`smbmap -u {{username}} --prompt -H {{ip}} -r`

- Afișează partajările SMB și listează recursiv un număr definit de niveluri de directoare și fișiere:

`smbmap -u {{username}} --prompt -H {{ip}} -R --depth {{3}}`

- Afișează partajările SMB și listează recursiv directoare și fișiere, descărcând fișierele care corespund unei expresii regulate:

`smbmap -u {{username}} --prompt -H {{ip}} -R -A {{pattern}}`

- Afișează partajările SMB și listează recursiv directoare și fișiere, căutând conținutul fișierelor care corespund unei expresii regulate:

`smbmap -u {{username}} --prompt -H {{ip}} -R -F {{pattern}}`

- Executați o comandă shell pe un sistem la distanță:

`smbmap -u {{username}} --prompt -H {{ip}} -x {{command}}`

- Încărcați un fișier pe un sistem la distanță:

`smbmap -u {{username}} --prompt -H {{ip}} --upload {{source}} {{destination}}`
