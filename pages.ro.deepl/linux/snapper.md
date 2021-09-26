# snapper

> Instrument de gestionare a instantaneelor din sistemul de fișiere.
> Mai multe informații: <http://snapper.io/manpages/snapper.html>.

- Listează configurațiile instantanee:

`snapper list-configs`

- Creați configurația snapper:

`snapper -c {{config}} create-config {{path/to/directory}}`

- Creați un instantaneu cu o descriere:

`snapper -c {{config}} create -d "{{snapshot_description}}"`

- Listează instantanee pentru o configurație:

`snapper -c {{config}} list`

- Ștergeți un instantaneu:

`snapper -c {{config}} delete {{snapshot_number}}`

- Ștergeți o serie de instantanee:

`snapper -c {{config}} delete {{snapshot_X}}-{{snapshot_Y}}`
