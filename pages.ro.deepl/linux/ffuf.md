# ffuf

> Instrument de descoperire a subdomeniilor și a directoarelor.
> Mai multe informații: <https://github.com/ffuf/ffuf>.

- Descoperă directoare folosind o listă [w]ordlist pe o [u]rl țintă cu ieșire [c]olorizată și [v]erbose:

`ffuf -w {{path/to/wordlist}} -u {{https://target/FUZZ}} -c -v`

- Fuzz host-[H]eaders cu un fișier gazdă pe un site web traget și [m]atch HTTP 200 [c]ode responses:

`ffuf -w {{hosts.txt}} -u {{https://example.org}} -H "{{Host: FUZZ}}" -mc {{200}}`

- Descoperă directoare utilizând o listă [w]ordlist pe un site web țintă cu un timp maxim de lucru individual de 60 de secunde și o profunzime de descoperire a recursivității de 2 niveluri:

`ffuf -w {{path/to/wordlist}} -u {{https://target/FUZZ}} -maxtime-job {{60}} -recursion -recursion-depth {{2}}`

- Parametru GET Fuzz pe un site web țintă și [f]ilter out mesaj [s]ize răspuns de 4242 bytes:

`ffuf -w {{path/to/param_names.txt}} -u {{https://target/script.php?FUZZ=test_value}} -fs {{4242}}`

- Metoda Fuzz POST cu POST [d]ata de parolă pe un site web țintă și [f]ilterarea răspunsului HTTP [c]ode 401:

`ffuf -w {{path/to/postdata.txt}} -X {{POST}} -d "{{username=admin\&password=FUZZ}}" -u {{https://target/login.php}} -fc {{401}}`

- Descoperiți subdomeniile folosind o listă de subdomenii pe un site web țintă:

`ffuf -w {{subdomains.txt}} -u {{https://website.com}} -H "{{Host: FUZZ.website.com}}"`
