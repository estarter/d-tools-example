This project is an example of [d-tools](https://github.com/estarter/d-tools) usage.

```bash
dbuild
dup
dlog server
dbash client
http server:8080/emails
sendemail -f from1@test.net -t recipient1@test.net -s server:25 -u "test $(date +%Y.%m.%d-%H:%M:%S)" -m "test email"
http server:8080/emails
http server:8080/delete
http server:8080/emails
```