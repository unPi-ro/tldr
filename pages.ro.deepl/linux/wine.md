# wine

> Rulați programe Windows pe Unix.
> Mai multe informații: <https://wiki.winehq.org/>.

- Rulați programul `ipconfig.exe`:

`wine {{ipconfig}} {{/all}}`

- Rulați `cmd.exe` în fundal:

`wine start {{cmd}}`

- Rulați Manager de pachete de tip Windows:

`wine uninstaller`

- Instalați pachetele MSI:

`wine msiexec /i {{package}}`
