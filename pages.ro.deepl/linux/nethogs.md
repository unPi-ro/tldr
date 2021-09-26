# nethogs

> Monitorizați utilizarea lățimii de bandă pentru fiecare proces.
> Mai multe informații: <https://github.com/raboof/nethogs>.

- Porniți nethogs ca root (dispozitivul implicit este eth0):

`sudo nethogs`

- Monitorizați lățimea de bandă pe un anumit dispozitiv:

`sudo nethogs {{device}}`

- Monitorizați lățimea de bandă pe mai multe dispozitive:

`sudo nethogs {{device1}} {{device2}}`

- Specificați rata de reîmprospătare:

`sudo nethogs -t {{seconds}}`
