# screenkey

> Un instrument de screencast pentru a afișa tastele apăsate.
> Mai multe informații: <https://www.thregr.org/~wavexx/software/screenkey/>.

- Afișează pe ecran tastele care sunt apăsate în prezent:

`screenkey`

- Afișează pe ecran tastele și butoanele mouse-ului care sunt apăsate în prezent:

`screenkey --mouse`

- Lansați meniul de setări al screenkey:

`screenkey --show-settings`

- Lansarea tastei ecranului într-o anumită poziție:

`screenkey --position {{top|center|bottom|fixed}}`

- Modificați formatul modificatorilor de taste afișate pe ecran:

`screenkey --mods-mode {{normal|emacs|mac|win|tux}}`

- Modificați aspectul tastelor de ecran:

`screenkey --bg-color "{{#a1b2c3}}" --font {{Hack}} --font-color {{yellow}} --opacity {{0.8}}`

- Trageți și selectați o fereastră pe ecran pentru a afișa tasta de ecran:

`screenkey --position fixed --geometry {{$(slop -n -f '%g')}}`
