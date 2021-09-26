# dmidecode

> Afișează conținutul tabelului DMI (cunoscut alternativ ca SMBIOS) într-un format lizibil pentru oameni.
> Necesită privilegii de root.
> Mai multe informații: <https://manned.org/dmidecode>.

- Afișați tot conținutul tabelului DMI:

`sudo dmidecode`

- Afișează versiunea BIOS:

`sudo dmidecode -s bios-version`

- Afișați numărul de serie al sistemului:

`sudo dmidecode -s system-serial-number`

- Afișează informații BIOS:

`sudo dmidecode -t bios`

- Afișează informații despre CPU:

`sudo dmidecode -t processor`

- Afișează informații despre memorie:

`sudo dmidecode -t memory`
