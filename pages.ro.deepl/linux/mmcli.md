# mmcli

> Controlați și monitorizați ModemManager.
> Mai multe informații: <https://www.freedesktop.org/software/ModemManager/man/latest/mmcli.1.html>.

- Lista mesajelor SMS disponibile pe modem:

`sudo mmcli --modem={{modem}} --messaging-list-sms`

- Șterge un mesaj de pe modem, specificând calea acestuia:

`sudo mmcli --modem={{modem}} --messaging-delete-sms={{path/to/message_file}}`
