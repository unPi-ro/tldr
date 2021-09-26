# x11vnc

> Un server VNC care va activa VNC pe un server de afișare existent.
> În mod implicit, serverul se va închide automat odată ce toți clienții se deconectează de la el.

- Lansați un server VNC care permite conectarea mai multor clienți:

`x11vnc -shared`

- Lansați un server VNC în modul de vizualizare și care nu se va închide după ce ultimul client se deconectează:

`x11vnc -forever -viewonly`

- Lansarea unui server VNC pe un anumit afișaj și ecran (ambele începând de la indexul zero):

`x11vnc -display :{{display}}.{{screen}}`

- Lansați un server VNC pe ecranul implicit al celui de-al treilea afișaj:

`x11vnc -display :{{2}}`

- Lansați un server VNC pe cel de-al doilea ecran al primului afișaj:

`x11vnc -display :{{0}}.{{1}}`
