# $awaitMessageReactions
Начинает ожидание реакций на указанном сообщении в указанном канале. Если вы хотите чтобы бот реагировал на всех пользователей - укажите в опции фильтра everyone.
### Использование
```php
$awaitMessageReactions[канал;сообщение;фильтр;время;реакции;команды;ошибка?;данные?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал | айди канала где есть сообщение с реакциями | айди | Да | 
| сообщение | айди сообщения с реакциями | айди | Да | 
| фильтр | фильтр пользователей на которых будет реагировать бот | айди | Да |
| время | время ожидания реакций, после чего бот выдаст ошибку | время | Да |
| реакции | реакции, на которые бот будет реагировать | перечисление | Да |
| команды | названия ожидаемых команд, которые выполнятся при нажатии на реакции | перечисление | Да |
| ошибка | текст, который выведется когда закончится время а на реакцию никто не нажал | текст | Нет |
| данные | объект данных для ожидаемых команд | объект | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$awaitMessageReactions',
  code: `
$awaitMessageReactions[$channelId;$messageID;everyone;30min;:joy:;:white_check_mark:;hi;bye;gn;{}]`
})
```
