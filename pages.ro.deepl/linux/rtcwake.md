# rtcwake

> Introduceți o stare de repaus a sistemului până la ora de trezire specificată în raport cu ceasul BIOS.

- Afișează dacă este setată sau nu o alarmă:

`sudo rtcwake -m show -v`

- Suspendare în RAM și trezire după 10 secunde:

`sudo rtcwake -m mem -s {{10}}`

- Suspendare pe disc (economie de energie mai mare) și trezire 15 minute mai târziu:

`sudo rtcwake -m disk --date +{{15}}min`

- Îngheață sistemul (mai eficient decât suspend-to-RAM, dar este necesară versiunea 3.9 sau o versiune mai nouă a kernelului Linux) și se trezește la o dată și o oră date:

`sudo rtcwake -m freeze --date {{YYYYMMDDhhmm}}`

- Dezactivați o alarmă setată anterior:

`sudo rtcwake -m disable`

- Efectuați o execuție de probă pentru a trezi calculatorul la o anumită oră. (Apăsați Ctrl C pentru a anula):

`sudo rtcwake -m on --date {{hh:ss}}`
