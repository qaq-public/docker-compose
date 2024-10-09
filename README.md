# QAQ 
```bash
# create mysql8 database `uniauth` and `upload`
# create a lark application and set the secuity url https://qaq.openqaq.fun/web/login/callback
# generate rsa key [how to generate](https://github.com/blacklee123/login)
cp .env.sample .env
# edit .env set the correct value
docker network create qaq-network
docker compose up
```