# raw-nginx-app

This app demonstrates usage of an nginx docker container serving static assets of a SPA.

## Instructions

```sh
pnpm i
pnpm build
docker build . -t nginx-test
docker run -p 8080:8080 nginx-test
```

You will see the app running now on <http://localhost:8080>.
