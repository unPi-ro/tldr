# physlock

> Blocați toate consolele și terminalele virtuale.
> Mai multe informații: <http://github.com/muennich/physlock>.

- Blochează fiecare consolă (este necesar ca utilizatorul curent sau root să o deblocheze):

`physlock`

- Dezactivarea mesajelor kernelului pe consolă în timp ce este blocat:

`physlock -m`

- Dezactivează mecanismul SysRq în timp ce este blocat:

`physlock -s`

- Afișați un mesaj înainte de solicitarea parolei:

`physlock -p "{{Locked!}}"`

- Fork and detach physlock (util pentru scripturile de suspendare sau hibernare):

`physlock -d`
