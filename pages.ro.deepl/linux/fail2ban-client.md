# fail2ban-client

> Configurați și controlați serverul fail2ban.
> Mai multe informații: <https://github.com/fail2ban/fail2ban>.

- Obține starea actuală a serviciului de închisoare:

`fail2ban-client status {{jail}}`

- Elimină IP-ul specificat din lista de interdicții a serviciului de închisoare:

`fail2ban-client set {{jail}} unbanip {{ip}}`

- Verificați dacă serverul fail2ban este în viață:

`fail2ban-client ping`
