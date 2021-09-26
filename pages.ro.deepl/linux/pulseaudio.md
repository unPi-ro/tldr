# pulseaudio

> Daemonul și managerul sistemului de sunet PulseAudio.
> Mai multe informații: <https://www.freedesktop.org/wiki/Software/PulseAudio/>.

- Verifică dacă PulseAudio rulează (un cod de ieșire diferit de zero înseamnă că nu rulează):

`pulseaudio --check`

- Porniți demonul PulseAudio în fundal:

`pulseaudio --start`

- Opriți daimonul PulseAudio în curs de execuție:

`pulseaudio --kill`

- Lista modulelor disponibile:

`pulseaudio --dump-modules`

- Încarcă un modul în daemonul care rulează în prezent cu argumentele specificate:

`pulseaudio --load="{{module_name}} {{arguments}}"`
