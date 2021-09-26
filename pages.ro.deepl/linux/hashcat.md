# hashcat

> Rapid și avansat instrument de recuperare a parolei.
> Mai multe informații: <https://manned.org/hashcat>.

- Efectuați un atac prin forță brută (modul 3) cu masca hashcat implicită:

`hashcat --hash-type {{hash_type_id}} --attack-mode {{3}} {{hash_value}}`

- Efectuați un atac prin forță brută (modul 3) cu un model cunoscut de 4 cifre:

`hashcat --hash-type {{hash_type_id}} --attack-mode {{3}} {{hash_value}} "{{?d?d?d?d}}"`

- Efectuați un atac prin forță brută (modul 3) utilizând cel mult 8 din toate caracterele ASCII imprimabile:

`hashcat --hash-type {{hash_type_id}} --attack-mode {{3}} --increment {{hash_value}} "{{?a?a?a?a?a?a?a?a}}"`

- Efectuați un atac de dicționar (modul 0) utilizând lista de cuvinte RockYou a unei cutii Kali Linux:

`hashcat --hash-type {{hash_type_id}} --attack-mode {{0}} {{hash_value}} {{/usr/share/wordlists/rockyou.txt}}`

- Efectuați un atac de dicționar bazat pe reguli (modul 0) utilizând lista de cuvinte RockYou modificată cu variante comune de parole:

`hashcat --hash-type {{hash_type_id}} --attack-mode {{0}} --rules-file {{/usr/share/hashcat/rules/best64.rule}} {{hash_value}} {{/usr/share/wordlists/rockyou.txt}}`

- Efectuați un atac combinat (modul 1) folosind concatenarea de cuvinte din două dicționare personalizate diferite:

`hashcat --hash-type {{hash_type_id}} --attack-mode {{1}} {{hash_value}} {{/path/to/dictionary1.txt}} {{/path/to/dictionary2.txt}}`

- Afișează rezultatul unui hash deja spart:

`hashcat --show {{hash_value}}`
