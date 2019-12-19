# emtsv Secure

Secure deployment of [emtsv](https://github.com/dlt-rilmta/emtsv)

### Usage

```
htpasswd -c .htpasswd emtsv
# type password
# re-type password

docker-compose up -d
```

It will be reachable on localhost:8080 with basic authentication.
