# genie

> Configurați și utilizați un spațiu de nume "bottle" pentru a rula systemd în cadrul WSL (Windows Subsystem for Linux).
> Pentru a le rula din Windows și nu de pe o distribuție care rulează deja, precedați-le cu `wsl`.
> Mai multe informații: <https://github.com/arkane-systems/genie>.

- Inițializarea sticlei (se execută o singură dată, la pornire):

`genie -i`

- Rulați un shell de autentificare în interiorul sticlei:

`genie -s`

- Execută o comandă specificată în interiorul sticlei:

`genie -c {{command}}`
