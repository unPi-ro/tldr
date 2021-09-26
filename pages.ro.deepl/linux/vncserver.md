# vncserver

> Lansează un desktop VNC (Virtual Network Computing).

- Lansați un server VNC pe următorul ecran disponibil:

`vncserver`

- Lansarea unui server VNC cu o anumită geometrie a ecranului:

`vncserver --geometry {{width}}x{{height}}`

- Oprește o instanță a serverului VNC care rulează pe un anumit ecran:

`vncserver --kill :{{display_number}}`
