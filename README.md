# Next 13 boilerplate

project with next 13 app routing, tailwindcss, react context

## Requirement

- [x] npm install

- [x] set .env (.env.local, .env.production ...)

./.env.template
```
# Choose development or production
NODE_ENV=development
NEXT_PUBLIC_SERVER_HOST=localhost:8000

# Choose http protocol that is http or https
NEXT_PUBLIC_HTTP_PROTOCOL_TYPE=http

# Choose websocket protocol that is ws or wss
NEXT_PUBLIC_WEBSOCKET_PROTOCOL_TYPE=ws

NEXT_PUBLIC_APP_URL='http://localhost:3000'
```

## Build

You have to install docker and docker compose

``` shell
# build
docker-compose up -d --build

# clean
docker rm -f app nginx
docker rmi app nginx
```


If you see more about our project, go to https://github.com/knock-version-1-0
