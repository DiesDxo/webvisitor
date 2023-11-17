# 🤖 BOT VISITOR PROXY

Bot visitor is used (GET HTTP) to send traffic to the target web/blog where this bot uses a proxy to determine different IP addresses.

This bot uses 1000 user-agents which can send to different types of devices used, to avoid spam detection on the target website. So you don't need to bother adding a user-agent, you only need to add the Proxy and Host Referers that you want to use. 

Don't use Host Referrers for pornography, gambling, or anything else. Because it can cause the targeted website/blog to become non-indexed by Google

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
cd webvisitor
```

```bash
set your api token in main.js

set your proxy in proxy.txt and 

set host referer in referers.txt
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
 
## 📢 Information

It should be noted that this bot must use a `Proxy (HTTP).` If it doesn't use a proxy, this bot will `NOT` be able to run. I suggest using `20-50 Residental Proxy (HTTP)` for Socks5 or others I haven't tried, you can try it yourself.

I dedicate it to people who are tired of waiting for a long time to index their website/blog, maybe this will help a little. I am not responsible if someone abuses this script to send traffic continuously without stopping, because it can cause non-indexing, aka the loss of the web/blog index from Google. 

`Use as necessary, take your own risk!`