# uvcdynctrl

> Un instrument de linie de comandă libwebcam pentru a gestiona controalele dinamice în uvcvideo.

- Enumerați toate camerele disponibile:

`uvcdynctrl -l`

- Specificați dispozitivul care urmează să fie utilizat (valoarea implicită este `video0`):

`uvcdynctrl -d {{device_name}}`

- Lista controalelor disponibile:

`uvcdynctrl -c`

- Setați o nouă valoare de control (pentru valori negative, adăugați -- înainte de {{-valoare}}):

`uvcdynctrl -s {{control_name}} {{value}}`

- Obține valoarea curentă a controlului:

`uvcdynctrl -g {{control_name}}`

- Salvează starea comenzilor curente într-un fișier:

`uvcdynctrl -W {{filename}}`

- Încarcă starea controalelor dintr-un fișier:

`uvcdynctrl -L {{filename}}`
