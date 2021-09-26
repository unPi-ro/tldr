# snmpwalk

> Instrument de interogare SNMP.
> Mai multe informații: <https://manned.org/snmpwalk>.

- Interoghează informațiile de sistem ale unei gazde de la distanță utilizând SNMPv1 și un șir de comunitate:

`snmpwalk -v1 -c {{community}} {{ip}}`

- Interoghează informațiile de sistem de pe o gazdă la distanță prin OID utilizând SNMPv2 pe un port specificat:

`snmpwalk -v2c -c {{community}} {{ip}}:{{port}} {{oid}}`

- Interogarea informațiilor de sistem pe o gazdă la distanță prin OID utilizând SNMPv3 și autentificarea fără criptare:

`snmpwalk -v3 -l {{authNoPriv}} -u {{username}} -a {{MD5|SHA}} -A {{passphrase}} {{ip}} {{oid}}`

- Interoghează informații de sistem pe o gazdă la distanță prin OID utilizând SNMPv3, autentificare și criptare:

`snmpwalk -v3 -l {{authPriv}} -u {{username}} -a {{MD5|SHA}} -A {{auth_passphrase}} -x {{DES|AES}} -X {{enc_passphrase}} {{ip}} {{oid}}`

- Interogarea informațiilor de sistem de pe o gazdă la distanță prin OID utilizând SNMPv3 fără autentificare sau criptare:

`snmpwalk -v3 -l {{noAuthNoPriv}} -u {{username}} {{ip}} {{oid}}`
