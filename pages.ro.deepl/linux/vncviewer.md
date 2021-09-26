# vncviewer

> Lansează un client VNC (Virtual Network Computing).

- Lansarea unui client VNC care se conectează la o gazdă pe un anumit ecran:

`vncviewer {{host}}:{{display_number}}`

- Lansare în modul ecran complet:

`vncviewer -FullScreen {{host}}:{{display_number}}`

- Lansarea unui client VNC cu o anumită geometrie a ecranului:

`vncviewer --geometry {{width}}x{{height}} {{host}}:{{display_number}}`

- Lansarea unui client VNC care se conectează la o gazdă pe un port dat:

`vncviewer {{host}}::{{port}}`
