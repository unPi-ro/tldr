# vcgencmd

> Imprimați informații de sistem pentru un Raspberry Pi.
> Mai multe informații: <https://www.raspberrypi.org/documentation/raspbian/applications/vcgencmd.md>.

- Enumeră toate comenzile disponibile:

`vcgencmd commands`

- Imprimă temperatura curentă a procesorului:

`vcgencmd measure_temp`

- Imprimă tensiunea curentă:

`vcgencmd measure_volts`

- Tipărește starea de strangulare a sistemului sub forma unui model de biți:

`vcgencmd get_throttled`

- Imprimați configurația bootloaderului (disponibilă numai pe modelele Raspberry Pi 4):

`vcgencmd bootloader_config`

- Ajutor pentru afișare:

`vcgencmd --help`
