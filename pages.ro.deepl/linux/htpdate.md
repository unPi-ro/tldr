# htpdate

> Sincronizarea datei și orei locale prin intermediul antetelor HTTP de la serverele web.
> Mai multe informații: <http://www.vervest.org/htp/>.

- Sincronizați data și ora:

`sudo htpdate {{host}}`

- Efectuați o simulare a sincronizării, fără nicio acțiune:

`htpdate -q {{host}}`

- Compensează deriva ceasului sistematic:

`sudo htpdate -x {{host}}`

- Setați ora imediat după sincronizare:

`sudo htpdate -s {{host}}`
