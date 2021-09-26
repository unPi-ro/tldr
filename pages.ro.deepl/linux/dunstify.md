# dunstify

> Un instrument de notificare care este o extensie a notify-send, dar care are mai multe caracteristici bazate pe dunst.
> Funcționează cu toate opțiunile care funcționează pentru notify-send.
> Mai multe informații: <https://wiki.archlinux.org/title/Dunst#Dunstify>.

- Afișează o notificare cu un titlu și un mesaj date:

`dunstify "{{Title}}" "{{Message}}"`

- Afișați o notificare cu o urgență specificată:

`dunstify "{{Title}}" "{{Message}}" -u {{low|normal|critical}}`

- Specificați un ID al mesajului (se suprascrie orice mesaj anterior cu același ID):

`dunstify "{{Title}}" "{{Message}}" -r {{123}}`

- Pentru a vedea alte opțiuni posibile:

`notify-send --help`
