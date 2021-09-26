# gsettings

> Consultați și modificați setările dconf cu validarea schemei.
> Mai multe informații: <https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/using_the_desktop_environment_in_rhel_8/configuring-gnome-at-low-level_using-the-desktop-environment-in-rhel-8#using-gsettings-command_configuring-gnome-at-low-level>.

- Setează valoarea unei chei. Nu reușește dacă cheia nu există sau dacă valoarea este în afara intervalului:

`gsettings set {{org.example.schema}} {{example-key}} {{value}}`

- Tipărește valoarea unei chei sau valoarea implicită furnizată de schemă dacă cheia nu a fost setată în `dconf`:

`gsetings get {{org.example.schema}} {{example-key}}`

- Dezafectează o cheie, astfel încât să fie utilizată valoarea implicită din schemă:

`gsettings reset {{org.example.schema}} {{example-key}}`

- Afișează toate schemele, cheile și valorile (nedeplasabile):

`gsettings list-recursively`

- Afișează toate cheile și valorile (implicit dacă nu este setat) dintr-o singură schemă:

`gsettings list-recursively {{org.example.schema}}`

- Afișează valorile permise de schemă pentru o cheie (util în cazul cheilor enum):

`gsettings range {{org.example.schema}} {{example-key}}`

- Afișează descrierea lizibilă de către om a unei chei:

`gsettings describe {{org.example.schema}} {{example-key}}`
