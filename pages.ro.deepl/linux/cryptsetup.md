# cryptsetup

> Gestionați volumele criptate simplu dm-crypt și LUKS (Linux Unified Key Setup).
> Mai multe informații: <https://gitlab.com/cryptsetup/cryptsetup/>.

- Inițializarea unui volum LUKS (suprascrie toate datele de pe partiție):

`cryptsetup luksFormat {{/dev/sda1}}`

- Deschideți un volum LUKS și creați o mapare decriptată la `/dev/mapper/{{target}}`:

`cryptsetup luksOpen {{/dev/sda1}} {{target}}`

- Îndepărtați o cartografiere existentă:

`cryptsetup luksClose {{target}}`

- Modificați fraza de acces a volumului LUKS:

`cryptsetup luksChangeKey {{/dev/sda1}}`
