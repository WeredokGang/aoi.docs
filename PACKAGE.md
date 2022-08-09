#  О библиотеке
<p align="center">
  <a href="https://aoi.js.org">
    <img width="200" src="https://cdn.discordapp.com/attachments/804813961190572093/924765606056701952/aoits.png">
  </a>
</p>

<h1 align="center">aoi.js</h1>

<div align="center">

**Продвинутый инструмент для создания вашего бота на node.js.**
    
[![NPM версия][npm-image]][npm-url]
[![AoiJS сервер][aoijs-server]][aoijs-server-url]
[![NPM установки][download-image]][download-url]

**Заменитель библиотеки [dbd.js](https://www.npmjs.com/package/dbd.js)**

[npm-image]: http://img.shields.io/npm/v/aoi.js.svg?style=flat-square
[npm-url]: http://npmjs.org/package/aoi.js
[download-image]: https://img.shields.io/npm/dt/aoi.js.svg?style=flat-square
[download-url]: https://npmjs.org/package/aoi.js
[aoijs-server]: https://img.shields.io/discord/773352845738115102?color=5865F2&logo=discord&logoColor=white
[aoijs-server-url]: https://aoi.js.org/invite
    
</div>

## Возможности

- Поддержка музыкальных команд
- Возможность создания мульти-интерактивных команд
- Ваши собственные настраиваемые функции
- 600+ доступных функций!
 
## Установка

**Node.JS версии 16.6.0 или выше необходим для работы с пакетом.**  


```bash
npm install aoi.js
```

```bash
yarn add aoi.js
```

## Пример использования
### Главный файл
```javascript
const aoijs = require("aoi.js")

const bot = new aoijs.Bot({
token: "токен",
prefix: "префикс",
intents: ["GUILDS", "GUILD_MESSAGES"]
})

//Ивенты
bot.onMessage()

//Пример команды
bot.command({
name: "ping",
code: `Понг! $pingms`
})

//Ивент при запуске 
bot.readyCommand({
    channel: "",
    code: `$log[Запущено $userTag[$clientID]]`
})
```

### Дополнительные пакеты


- [@akarui/aoi.music](https://www.npmjs.com/package/@akarui/aoi.music) для музыкальных функций (`npm install @akarui/aoi.music`)

## Разработано Akarui Development

<p align="center">
  <a href="https://aoi.js.org/invite">
    <img width="350" src="https://cdn.discordapp.com/attachments/804813961190572093/909447704978001931/Akarui_Development_Banner.png">
  </a>
</p>

    
## Ссылки
- [Официальный веб-сайт](https://aoi.js.org)
- [NPM](https://www.npmjs.com/package/aoi.js)
- [Гитхаб](https://github.com/AkaruiDevelopment/aoi.js)
- [Дискорд сервер](https://discord.gg/HMUfMXDQsV)
- [Документация](https://akarui.leref.ga/v/aoi.js/)
