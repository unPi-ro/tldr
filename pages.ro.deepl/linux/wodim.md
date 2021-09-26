# wodim

> Comandă (denumită `cdrecord` pe unele sisteme) pentru înregistrarea de date pe CD-uri sau DVD-uri.
> Unele invocări ale wodim pot cauza acțiuni distructive, cum ar fi ștergerea tuturor datelor de pe un disc.

- Afișează unitățile optice disponibile pentru `wodim`:

`wodim --devices`

- Înregistrați ("ardeți") un disc numai audio:

`wodim dev=/dev/{{optical_drive}} -audio {{track*.cdaudio}}`

- Ardeți un fișier pe un disc, ejectați discul odată ce ați terminat (unele aparate de înregistrare necesită acest lucru):

`wodim -eject dev=/dev/{{optical_drive}} -data {{file.iso}}`

- Arderea unui fișier pe discul unei unități optice, cu posibilitatea de a scrie pe mai multe discuri succesiv:

`wodim -tao dev=/dev/{{optical_drive}} -data {{file.iso}}`
