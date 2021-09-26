# authconfig

> O interfață CLI pentru configurarea resurselor de autentificare a sistemului.
> Mai multe informații: <https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/system-level_authentication_guide/authconfig-install>.

- Afișarea configurației curente (sau a rulării uscate):

`authconfig --test`

- Configurați serverul pentru a utiliza un alt algoritm de hashing al parolei:

`authconfig --update --passalgo={{algorithm}}`

- Activați autentificarea LDAP:

`authconfig --update --enableldapauth`

- Dezactivați autentificarea LDAP:

`authconfig --update --disableldapauth`

- Activați Network Information Service (NIS):

`authconfig --update --enablenis`

- Activați Kerberos:

`authconfig --update --enablekrb5`

- Activați autentificarea Winbind (Active Directory):

`authconfig --update --enablewinbindauth`

- Activați autorizarea locală:

`authconfig --update --enablelocauthorize`
