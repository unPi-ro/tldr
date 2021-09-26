# xfce4-terminal

> Emulatorul de terminal XFCE4.
> Mai multe informații: <https://docs.xfce.org/apps/xfce4-terminal/start>.

- Deschideți o nouă fereastră de terminal:

`xfce4-terminal`

- Setați titlul inițial:

`xfce4-terminal --initial-title "{{initial_title}}"`

- Deschideți o filă nouă în fereastra curentă a terminalului:

`xfce4-terminal --tab`

- Executarea unei comenzi într-o nouă fereastră de terminal:

`xfce4-terminal --command "{{command_with_args}}"`

- Păstrați terminalul în preajmă după ce comanda executată se termină de executat:

`xfce4-terminal --command "{{command_with_args}}" --hold`

- Deschideți mai multe file noi, executând o comandă în fiecare dintre ele:

`xfce4-terminal --tab --command "{{command_a}}" --tab --command "{{command_b}}"`
