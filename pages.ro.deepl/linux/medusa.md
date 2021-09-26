# Medusa

> Un program modular și paralel de forțare brută de autentificare pentru o varietate de protocoale.
> Mai multe informații: <https://manned.org/medusa>.

- Executarea prin forță brută împotriva unui server FTP utilizând un fișier care conține nume de utilizator și un fișier care conține parole:

`medusa -M ftp -h host -U {{path/to/username_file}} -P {{path/to/password_file}}`

- Execută o încercare de autentificare pe un server HTTP folosind numele de utilizator, parola și user-agent specificate:

`medusa -M HTTP -h host -u {{username}} -p {{password}} -m USER-AGENT:"{{Agent}}"`

- Executați o forță brută împotriva unui server MySQL folosind un fișier care conține nume de utilizator și un hash:

`medusa -M mysql -h host -U {{path/to/username_file}} -p {{hash}} -m PASS:HASH`

- Executați o forță brută împotriva unei liste de servere SMB utilizând un nume de utilizator și un fișier pwdump:

`medusa -M smbnt -H {{path/to/hosts_file}} -C {{path/to/pwdump_file}} -u {{username}} -m PASS:HASH`
