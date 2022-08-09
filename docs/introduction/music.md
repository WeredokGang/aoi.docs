# Музыка
Начиная с версии aoi.js v5 появилась возможность вновь использовать музыку. Данный пакет даёт вам возможность работать с музыкой разных платформ - youtube, spotify, soundcloud а так-же локальные - ссылки на треки или путь к файлу с треком
## Установка

```
npm i @akarui/aoi.music
```

## Настройка в aoi.js

После установки aoi.music, нужно настроить отдельный класс для музыки в главном файле. Пример:

```js
const aoijs = require("aoi.js");

const bot = new aoijs.bot({
  token: "DISCORD BOT TOKEN",
  prefix: ".",
  intents: ["guilds", "guildMessages", "guildVoiceStates"], //Интент guildVoiceStates является обязательным
});

const loader = new aoijs.LoadCommands(bot);

const voice = new aoijs.Voice(
  bot,
  {
    cache: {
      cacheType: "Memory",//Кэширование музыки
      enabled: true,
    }
  },
  true, //для включения pruneMusic 
);

voice.onTrackStart();

loader.load(bot.cmd, "./Commands/commands/"); //загрузчик обычных команд
loader.load(voice.cmd, "./Commands/voice/"); //загрузчик музыкальных команд
```
}
## Использование класса Voice

Поскольку мы добавили класс Voice в индекс.js и загрузчик в голосовую папку, настройка класса Voice завершена. Давайте создадим некоторые голосовые команды.
## Play(Воспроизвести)
```js
//Commands/commands/play.js
module.exports = {
  name: "play youtube",
  $if: "v4", 
  code: `
    $let[msg;$playTrack[youtube;$message]]

    $if[$hasPlayer==false]
        $joinVc
    $endif


    `,
};
```
## Queue(Очередь)
```js
//Commands/commands/queue.js
module.exports = {
  name: "queue",
  code: `
   $title[1;Queue]
   $author[1;Запрошено $usertag;$authorAvatar]
   $description[1;$queue[$if[$message==;1;$message]]]
   $footer[1;количество песен ->$queueLength]
   $color[1;RANDOM]
   $addTimestamp[1]
    `,
};
```
## onTrackStart ивент
```js
//Commands/voice/trackStart.js
module.exports = {
  name: "отправить когда трек запуститься", //опционально
  type : "trackStart",
  channel : "$channelId",
  code: `
      $title[1;Сейчас играет...]
      $description[1;$if[$musicEventData[info.description]==;Описание не доступно;$musicEventData[info.description]]]
      $color[1;RANDOM]
      $author[1;$musicEventData[info.title]]
      $image[1;$musicEventData[info.thumbnail]]
    `,
};
```

