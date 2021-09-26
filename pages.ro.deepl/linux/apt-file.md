# apt-file

> Căutați fișiere în pachetele apt, inclusiv în cele care nu sunt încă instalate.
> Mai multe informații: <https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

- Actualizarea bazei de date cu metadate:

`sudo apt update`

- Caută pachetele care conțin fișierul sau calea specificată:

`apt-file {{search|find}} {{part/of/filename}}`

- Enumeră conținutul unui anumit pachet:

`apt-file {{show|list}} {{package_name}}`

- Caută pachete care se potrivesc cu expresia regulată dată în `pattern`:

`apt-file {{search|find}} --regexp {{regular_expression}}`
