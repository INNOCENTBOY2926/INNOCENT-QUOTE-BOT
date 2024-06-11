# quote-bot
Telegram quote bot

[![time tracker](https://wakatime.com/badge/github/LyoSU/quote-bot.svg)](https://wakatime.com/badge/github/LyoSU/quote-bot)


# Docker installation
1) Pull this repo

2) Pull [quote_api](https://github.com/LyoSU/quote-api)

3) Edit both `.env` files in repos

4) Create network `docker network create quotly`

5) Compile/Download tdlib for linux and place it to `helpers/tdlib/data/libtdjson/libtdjson.so`. To make it easier, check out [this builder](https://github.com/vlakam/tdlib.native) or [this AppVeyor CI](https://ci.appveyor.com/project/vlakam/tdlib-native) (ubuntu > Artifacts > linux) or the [prebuilt-tdlib](https://npmjs.com/package/prebuilt-tdlib) npm package


<h3 align="center">
    ─「 ᴅᴇᴩʟᴏʏ ᴏɴ ʜᴇʀᴏᴋᴜ 」─
</h3>

<p align="center"><a href="https://dashboard.heroku.com/new?template=https://github.com/INNOCENTBOY2926/INNOCENT-QUOTE-BOT"> <img src="https://img.shields.io/badge/Deploy%20On%20Heroku-red?style=for-the-badge&logo=heroku" width="520" height="138.45"/></a></p>
6) `docker-compose up -d` on both repos
