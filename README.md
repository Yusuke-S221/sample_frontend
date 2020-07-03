# front

> My luminous Nuxt.js project

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## DB Setup

```bash
docker-compose exec app php artisan migrate:fresh
docker-compose exec app php artisan db:seed
```
