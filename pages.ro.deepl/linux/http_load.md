# http_load

> Un instrument de analiză comparativă HTTP.
> Execută mai multe căutări HTTP în paralel pentru a testa capacitatea de procesare a unui server web.
> Mai multe informații: <http://www.acme.com/software/http_load/>.

- Emulați 20 de solicitări pe baza unui anumit fișier de listă URL pe secundă, timp de 60 de secunde:

`http_load -rate {{20}} -seconds {{60}} {{path/to/urls.txt}}`

- Emulați 5 solicitări simultane pe baza unui fișier de listă URL dat, timp de 60 de secunde:

`http_load -parallel {{5}} -seconds {{60}} {{path/to/urls.txt}}`

- Emulați 1 000 de cereri la 20 de cereri pe secundă, pe baza unui fișier de listă URL dat:

`http_load -rate {{20}} -fetches {{1000}} {{path/to/urls.txt}}`

- Emulați 1000 de cereri la 5 cereri simultane la un moment dat, pe baza unui fișier de listă URL dat:

`http_load -parallel {{5}} -fetches {{1000}} {{path/to/urls.txt}}`
