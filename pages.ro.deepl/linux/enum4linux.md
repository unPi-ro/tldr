# enum4linux

> Instrument pentru enumerarea informațiilor despre Windows și Samba de pe sistemele de la distanță.
> Încearcă să ofere o funcționalitate similară cu enum.exe disponibil anterior la www.bindview.com.
> Mai multe informații: <https://labs.portcullis.co.uk/tools/enum4linux/>.

- Încercați să enumerați folosind toate metodele:

`enum4linux -a {{remote_host}}`

- Enumerare folosind datele de autentificare date:

`enum4liux -u {{user_name}} -p {{password}} {{remote_host}}`

- Listează numele de utilizator de la o anumită gazdă:

`enum4liux -U {{remote_host}}`

- Acțiuni de listă:

`enum4liux -S {{remote_host}}`

- Obțineți informații despre sistemul de operare:

`enum4liux -o {{remote_host}}`
