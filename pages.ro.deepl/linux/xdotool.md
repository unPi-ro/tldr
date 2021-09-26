# xdotool

> Automatizarea liniei de comandă pentru X11.

- Obține ID-ul ferestrei X-Windows al ferestrei (ferestrelor) Firefox care rulează:

`xdotool search --onlyvisible --name {{firefox}}`

- Faceți clic pe butonul din dreapta al mouse-ului:

`xdotool click {{3}}`

- Obține ID-ul ferestrei active în prezent:

`xdotool getactivewindow`

- Concentrați-vă pe fereastra cu ID-ul 12345:

`xdotool windowfocus --sync {{12345}}`

- Introduceți un mesaj, cu o întârziere de 500 ms pentru fiecare literă:

`xdotool type --delay {{500}} "Hello world"`

- Apăsați tasta Enter:

`xdotool key {{KP_Enter}}`
