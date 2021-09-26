# sic

> Client IRC simplu.
> O parte din uneltele fără sugativă.
> Mai multe informații: <https://tools.suckless.org/sic/>.

- Conectați-vă la gazda implicită (irc.ofct.net) cu porecla setată în variabila de mediu `$USER`:

`sic`

- Se conectează la o gazdă dată, folosind o poreclă dată:

`sic -h {{host}} -n {{nickname}}`

- Se conectează la o anumită gazdă, folosind o poreclă și o parolă date:

`sic -h {{host}} -n {{nickname}} -k {{password}}`

- Alăturați-vă unui canal:

`:j #{{channel}}<Enter>`

- Trimiteți un mesaj către un canal sau un utilizator:

`:m #{{channel|user}}<Enter>`

- Setați canalul sau utilizatorul implicit:

`:s #{{channel|user}}<Enter>`
