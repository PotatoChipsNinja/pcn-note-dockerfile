## leanote docker-compose configs

[LEANOTE](http://leanote.com/) is a notebook platform, which you can host by yourself.

> Leanote, Not Just A Notebook!

## Build

```bash
git clone https://github.com/PotatoChipsNinja/pcn-note-dockerfile.git && cd pcn-note-dockerfile
docker-compose build
```

## Preparation

### `docker-compose.yml`

Change volumes of mongodb

### `conf/app.conf`

Focusing on these:

- `site.url`
- `app.secret`

## Run

```bash
docker-compose up -d
```
