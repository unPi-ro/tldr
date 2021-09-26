# pw-loopback

> Instrument pentru crearea de dispozitive loopback în pipewire.
> Mai multe informații: <https://gitlab.freedesktop.org/pipewire/pipewire/-/wikis/Virtual-Devices>.

- Creați un dispozitiv de buclă cu comportamentul de buclă implicit:

`pw-loopback`

- Creați un receptor care poate fi selectat în aplicațiile care redirecționează datele către un alt receptor:

`pw-loopback -m '{{[FL FR]}}' --capture-props='{{media.class=Audio/Sink node.name=my-sink}}'`

- Creați o chiuvetă care poate fi selectată în aplicații și care schimbă canalele stânga și dreapta cu o altă chiuvetă:

`pw-loopback --capture-props='{{media.class=Audio/Sink node.name=my-sink audio.position=[FL FR]}}' --playback-props='{{audio.position=[FR FL]}}'`

- Creați o sursă care poate fi selectată în aplicații care schimbă canalele stânga și dreapta de la o altă sursă:

`pw-loopback --capture-props='{{audio.position=[FR FL]}}' --playback-props='{{media.class=Audio/Source node.name=my-source audio.position=[FL FR]}}'`
