[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/naix0x/Bot-Visitor-Proxy/blob/main/LICENSE)
![GitHub repo size](https://img.shields.io/github/repo-size/naix0x/Bot-Visitor-Proxy)
![GitHub contributors](https://img.shields.io/github/contributors/naix0x/Bot-Visitor-Proxy)
![GitHub last commit](https://img.shields.io/github/last-commit/naix0x/Bot-Visitor-Proxy)
![GitHub forks](https://img.shields.io/github/forks/naix0x/Bot-Visitor-Proxy)
![GitHub issues](https://img.shields.io/github/issues-raw/naix0x/Bot-Visitor-Proxy)
![GitHub pull requests](https://img.shields.io/github/issues-pr/naix0x/Bot-Visitor-Proxy)
![GitHub stars](https://img.shields.io/github/stars/naix0x/Bot-Visitor-Proxy)


# 🤖 BOT VISITOR PROXY

<center><img src="demo image/Layer7-http.png" width=160></center>

Bot visitor is used `(GET HTTP)` to send traffic to the target web/blog where this bot uses a proxy to determine different `IP Addresses.`

This bot uses 1000 user-agents which can send to different types of devices used, to avoid spam detection on the target website. So you don't need to bother adding a user-agent, you only need to `add` the `Proxy` and `Host Referers` that you want to use. 

Don't use Host Referrers for `pornography`, `gambling`, or anything else. Because it can cause the targeted website/blog to become `non-indexed` by Google

## ⚒️ Command Management Access

The following is cmd management in bot :

| CMD       | Information |
|-----------|-------------|
| /send_visitor `url` `bot` `delay`    | example : `/send_visitor http://websitetarget.com 100 5` |
| /stop_visitor     | stop process bot |
| /getproxy     | viewing proxy list |
| /setproxy `user:pass@ip:port` or `ip:port`    | adding new proxy |
| /removeproxy `user:pass@ip:port` or `ip:port`    | remove proxy |
| /getreferers     | view referers list |
| /setreferer `http://example.com`    | set host referer |
| /removerefer `http://example.com`    | remove host referer |

## ⚠️ Warning
- must use `http://` like `/send_visitor http://targat.com 10 5`

## 📸 Demo Picture

[<img src="demo image/Screenshot_20231117-030527_Telegram.jpg" width=160>]
[<img src="demo image/Screenshot_20231117-030547_Telegram.jpg" width=160>]
[<img src="demo image/Screenshot_20231117-030646_Telegram.jpg" width=160>]
[<img src="demo image/Screenshot_20231117-030712_Telegram.jpg" width=160>]
[<img src="demo image/Screenshot_20231117-030805_Telegram.jpg" width=160>]
[<img src="demo image/Screenshot_20231129-234802_Telegram.png" width=160>]


## 🆕 Update Version

- Version 4.0.0 (29/11/2023)

Update running scripted without proxies 

- Version 3.3.4 (20/11/2023)

Fix bug send http:// error 

- Version 3.3.2 (18/11/2023)

I have added a proxy to support use with username and password, or without username and password, like `user:pass@ip:port` and `ip:port` 

## 📋 Requirements 

- for using this bot, requirements install needed for bot
```bash
apt-get update -y && apt-get upgrade -y
```

```bash
apt install nodejs git npm yarn
```

```bash
npm install node-telegram-bot-api axios-https-proxy-fix fs yarn
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
set your api token in config.js

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

 ̶I̶t̶ ̶s̶h̶o̶u̶l̶d̶ ̶b̶e̶ ̶n̶o̶t̶e̶d̶ ̶t̶h̶a̶t̶ ̶t̶h̶i̶s̶ ̶b̶o̶t̶ ̶m̶u̶s̶t̶ ̶u̶s̶e̶ ̶a̶ ̶`̶P̶r̶o̶x̶y̶ ̶(̶H̶T̶T̶P̶)̶.̶`̶ ̶I̶f̶ ̶i̶t̶ ̶d̶o̶e̶s̶n̶'̶t̶ ̶u̶s̶e̶ ̶a̶ ̶p̶r̶o̶x̶y̶,̶ ̶t̶h̶i̶s̶ ̶b̶o̶t̶ ̶w̶i̶l̶l̶ ̶`̶N̶O̶T̶`̶ ̶b̶e̶ ̶a̶b̶l̶e̶ ̶t̶o̶ ̶r̶u̶n̶.̶ I suggest using `20-50 Residental Proxy (HTTP)` for Socks5 or others I haven't tried, you can try it yourself.

`Now already support with running without proxies!`

I dedicate it to people who are tired of waiting for a long time to index their website/blog, maybe this will help a little. I am not responsible if someone abuses this script to send traffic continuously without stopping, because it can cause non-indexing, aka the loss of the web/blog index from Google. 

if there is an error in sending visitors, as in the demo photo that I have shown. This is not due to an error in the script, but rather an error from the proxy used, such as error 407 which means the proxy did not accept authentication.

If there is a bug, open an issue and I will fix it asap soon as possible.


`Use as necessary, take your own risk!`

## ⚠️ Another Project

If you think this is too complicated, you can use another project of mine, without a proxy and without using bots. because this shell script is used to flood http, here we go. [HTTP Flooder](https://github.com/naix0x/httprequest).
## 🤝 Contributing

If you find a bug or want a new feature in this bot, open an issue or pull request and for those who want to contribute to this bot script. Welcome and really appreciate it.

## 📝 License

This project is licensed under the [MIT License](https://github.com/naix0x/Bot-Visitor-Proxy/blob/main/LICENSE).

<img src="demo image/images (9).png" width=50>

## 🌟 Forks and Stars

If you find this project useful, please give it a star ⭐ and consider forking it 🍴 to support its development and help it reach a wider audience.

## ☕ Project usesless? 

If this project is very helpful, you can support me to be more enthusiastic about developing it

<a href="https://saweria.co/naix0x" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Buy Me A Coffee" width="150" ></a>

## 👤 Development

[![Mustofa Bovalone](https://github.com/naix0x.png?size=100)](https://github.com/naix0x) |
----|
[Mustofa Bovalone](https://t.me/maticstable) |
Author, Base, Bug Fixes  |
