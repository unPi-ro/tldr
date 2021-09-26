# openfortivpn

> Un client VPN, pentru soluția proprietară PPP SSL VPN a Fortinet.
> Mai multe informații: <https://github.com/adrienverge/openfortivpn>.

- Conectați-vă la un VPN cu un nume de utilizator și o parolă:

`openfortivpn --username={{username}} --password={{password}}`

- Conectați-vă la un VPN utilizând un fișier de configurare specific (valoarea implicită este `/etc/openfortivpn/config`):

`sudo openfortivpn --config={{path/to/config}}`

- Conectați-vă la un VPN specificând gazda și portul:

`openfortivpn {{host}}:{{port}}`

- Aveți încredere într-o anumită poartă de acces prin transmiterea sumei sha256 a certificatului său:

`openfortivpn --trusted-cert={{sha256_sum}}`
