# isoinfo

> Programe utilitare pentru descărcarea și verificarea imaginilor de disc ISO.
> Mai multe informații: <https://manned.org/isoinfo>.

- Enumeră toate fișierele incluse într-o imagine ISO:

`isoinfo -f -i {{path/to/image.iso}}`

- E[x]trageți un anumit fișier dintr-o imagine ISO și trimiteți-l pe stdout:

`isoinfo -i {{path/to/image.iso}} -x {{/PATH/TO/FILE/INSIDE/ISO.EXT}}`

- Afișează informațiile de antet pentru o imagine de disc ISO:

`isoinfo -d -i {{path/to/image.iso}}`
