## Push to production

1. Login to server with docker installed.
2. Clone this repo and go inside:
```bash
git clone https://github.com/deenoize/nginx-mongo-docker.git && cd nginx-mongo-docker
```

3. Get the latest version of nginx.tmpl file:
```bash
curl https://raw.githubusercontent.com/jwilder/nginx-proxy/master/nginx.tmpl > nginx.tmpl
```
4. Start docker-compose:
```bash
docker-compose up -d
```
