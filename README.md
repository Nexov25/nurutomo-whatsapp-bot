## Nurutomo WhatsApp Bot

Simple WhatsApp Bot By Nurutomo

<div align="center">
<details>
 <summary>Repo Asli</summary>
 
[Nurutomo](https://github.com/Nurutomo)
 
</details>
</div>

### FOR TERMUX AND SSH VPS USER

```bash
> apt update && apt upgrade
> apt install nodejs
> apt install git
> apt install ffmpeg
> apt install imagemagick
> git clone https://github.com/hirohito-xyz/nurutomo-wabot-aq.git
> cd nurutomo-wabot-aq
> npm start
scan qr nya
```

## NOTES 

Tinggal npm start aja

Gua Cuma Nambahin node_modules nya doang
Biar Langsung Scan qr

---------

## Arguments `node . [--options] [<session name>]`

### `--session <file name>`

Use another session with another name, default is ```session.data.json```

### `--prefix <prefixes>`

* `prefixes` are seperated by each character
Set prefix

### `--server`

Used for [heroku](https://heroku.com/) or scan through website

### `--db <json-server-url>`

Use external db instead of local db, 
Example Server `https://json-server.nurutomo.repl.co/`

Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

The server should have like this specification

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

If small qr unicode doesn't support

### `--img`

Enable image inspector through terminal

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```