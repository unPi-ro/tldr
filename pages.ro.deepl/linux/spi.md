# spi

> Un meta-gestionar de pachete care gestionează atât pachetele cât și slackbuilds.
> Mai multe informații: <https://github.com/gapan/spi>.

- Actualizarea listei de pachete și slackbuilds disponibile:

`spi --update`

- Instalați un pachet sau slackbuild:

`spi --install {{package/slackbuild_name}}`

- Actualizați toate pachetele instalate la cele mai recente versiuni disponibile:

`spi --upgrade`

- Localizați pachetele sau slackbuilds după numele sau descrierea pachetului:

`spi {{search_terms}}`

- Afișează informații despre un pachet sau despre slackbuild:

`spi --show {{package/slackbuild_name}}`

- Curățați memoria cache a pachetului local și a slackbuild:

`spi --clean`
