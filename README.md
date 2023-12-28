# Gitlab 

## SSL

```bash
$ openssl req -newkey rsa:4096 -nodes -sha256 -addext "subjectAltName = DNS:*.desarrollosur.com.ar" -keyout registry.desarrollosur.com.ar.key -x509 -days 3650 -out registry.desarrollosur.com.ar.crt
$ # Completar con los siguientes datos
Country Name (2 letter code) [AU]:AR
State or Province Name (full name) [Some-State]:TDF
Locality Name (eg, city) []:Ushuaia
Organization Name (eg, company) [Internet Widgits Pty Ltd]:Desarrollo Sur
Organizational Unit Name (eg, section) []:
Common Name (e.g. server FQDN or YOUR name) []:*.desarrollosur.com.ar
Email Address []:email@personal.com
```
