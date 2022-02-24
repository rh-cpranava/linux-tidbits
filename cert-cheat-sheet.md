# Check certs

* Check certs CA and validity
```
openssl s_client -showcerts -verify 5 -connect <url> < /dev/null
```
