# Загрузчик команд

Вы можете загружать свои команды из папок. Это удобно для сортирования всех ваших кодов по отдельным файлам в разных папках.
## Настройка класса
```js
const loader = new <библиотека>.LoadCommands(<клиент>)
loader.load(<клиент>.cmd, "./папка", true или false)
```
### Клиенты
Вы можете загружать два типа команд: обычные (от aoi.js) и голосовые (от @akarui/aoi.music). Учтите что нужно создавать отдельные папки для каждого клиента чтобы всё работало. Вы не можете загружать команды одной библиотеки в загрузчике другой 

## Папки
В этой опции вы должны указать папку, в которой должны загружаться все ваши команды. Вы можете указать лишь начальную папку, все подпапки будут тоже загружаться. Например, расположение файлов в папке:
```js
commands
 developer
  eval.js
  djsEval.js
  client.js
 moderation
  admin
   ban.js
   unban.js
  mods
   timeout.js
   warn.js
   unwarn.js
   untimeout.js
```
В классе это будет выглядеть так:
```javascript
loader.load(<клиент>.cmd, "./commands", true или false)
```

### Логирование загрузчика команд
В последней опции вы можете настраивать логирование с загрузчика. Например, если вя отите чтобы при запуске / обновлении команд бота вы могли видеть в консоли все команды: какие загрузились, какие нет то укажите true. Если же нет — false.

## Обновление команд без необходимости постоянно перезапускать сервер
Используя класс загрузчика команд вы получаете дополнительную возможность для разработки своего бота — функция $updateCommands будет обновлять ваш загрузчик команд без перезапуска бота.