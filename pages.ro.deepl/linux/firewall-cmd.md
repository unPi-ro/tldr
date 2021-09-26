# firewall-cmd

> Clientul de linie de comandă firewalld.
> Mai multe informații: <https://firewalld.org/documentation/man-pages/firewall-cmd>.

- Vizualizați zonele de firewall disponibile:

`firewall-cmd --get-active-zones`

- Vizualizați regulile care sunt aplicate în prezent:

`firewall-cmd --list-all`

- Mutați permanent interfața în zona de blocare, blocând efectiv toate comunicațiile:

`firewall-cmd --permanent --zone={{block}} --change-interface={{enp1s0}}`

- Deschide permanent portul pentru un serviciu din zona specificată (cum ar fi portul 443 în zona `public`):

`firewall-cmd --permanent --zone={{public}} --add-service={{https}}`

- Închide permanent portul pentru un serviciu din zona specificată (cum ar fi portul 80 în cazul în care se află în zona `public`):

`firewall-cmd --permanent --zone={{public}} --remove-service={{http}}`

- Deschide permanent două porturi arbitrare în zona specificată:

`firewall-cmd --permanent --zone={{public}} --add-port={{25565/tcp}} --add-port={{19132/udp}}`

- Reîncărcați firewalld pentru a forța modificările regulilor să intre în vigoare:

`firewall-cmd --reload`
