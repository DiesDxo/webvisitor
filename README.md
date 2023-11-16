# 🤖 BOT VISITOR PROXY

Bot visitor is used (GET HTTP) to send traffic to the target web/blog where this bot uses a proxy to determine different IP addresses.

## ⚒️ Command Management Access

The following is cmd management in bot :

| CMD       | Information |
|-----------|-------------|
| /send_visitor `url` `bot` `delay`    | example : /send_visitor 100 5 |
| /stop_visitor     | stop process bot |
| /getproxy     | viewing proxy list |
| /setproxy `ip:port`    | adding new proxy |
| /removeproxy `ip:port`    | remove proxy |
| /getreferers     | view referers list |
| /setreferer `http://example.com`    | set host referer |
| /removerefer `http://example.com`    | remove host referer |

## 📋 Requirements 

- for using this bot, requirements install needed for bot
```bash
apt-get update -y && apt-get upgrade -y
```

```bash
apt install nodejs git npm yarn
```

```bash
npm install requirements.txt
```

## 🚀 Run this bot

- Prepare youre API Token telegram.

```bash
npm install webvisitor
```

```bash
mv node_modules/webvisitor ./
```

```bash
setting your api token in main.js 
```

- and for run this bot
```bash
yarn start
```

- if you need this bot run on background
```javascript
npm install pm2
```
- and run this command
```javascript
npx pm2 start main.js
```
- for stop command
```javascript
npx pm2 stop main.js
```
 
