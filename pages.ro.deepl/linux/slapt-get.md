# slapt-get

> Un sistem asemănător lui apt pentru gestionarea pachetelor Slackware.
> Sursele pachetelor trebuie să fie configurate în fișierul slapt-getrc.

- Actualizați lista de pachete și versiuni disponibile:

`slapt-get --update`

- Instalați un pachet sau actualizați-l la cea mai recentă versiune disponibilă:

`slapt-get --install {{package_name}}`

- Îndepărtați un pachet:

`slapt-get --remove {{package_name}}`

- Actualizați toate pachetele instalate la cele mai recente versiuni disponibile:

`slapt-get --upgrade`

- Localizați pachetele după numele pachetului, setul de discuri sau versiunea:

`slapt-get --search {{package_name}}`

- Afișează informații despre un pachet:

`slapt-get --show {{package_name}}`
