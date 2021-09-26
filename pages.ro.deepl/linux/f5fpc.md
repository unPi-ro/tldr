# f5fpc

> Un client SSL VPN proprietar comercial de BIG-IP Edge.
> Mai multe informații: <https://techdocs.f5.com/kb/en-us/products/big-ip_apm/manuals/product/apm-client-configuration-11-4-0/4.html>.

- Deschideți o nouă conexiune VPN:

`sudo f5fpc --start`

- Deschideți o nouă conexiune VPN la o anumită gazdă:

`sudo f5fpc --start --host {{host.example.com}}`

- Specificați un nume de utilizator (utilizatorului i se va solicita o parolă):

`sudo f5fpc --start --host {{host.example.com}} --username {{user}}`

- Afișează starea curentă a VPN-ului:

`sudo f5fpc --info`

- Închideți conexiunea VPN:

`sudo f5fpc --stop`
