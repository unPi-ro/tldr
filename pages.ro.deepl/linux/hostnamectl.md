# hostnamectl

> Obțineți sau setați numele de gazdă al computerului.
> Mai multe informații: <https://manned.org/hostnamectl>.

- Obține numele de gazdă al computerului:

`hostnamectl`

- Setați numele de gazdă al computerului:

`sudo hostnamectl set-hostname "{{hostname}}"`

- Setați un nume de gazdă frumos pentru computer:

`sudo hostnamectl set-hostname --static "{{hostname.example.com}}" && sudo hostnamectl set-hostname --pretty "{{hostname}}"`

- Resetează numele de gazdă la valoarea sa implicită:

`sudo hostnamectl set-hostname --pretty ""`
