# $awaitCmdReactions
  Начинает ожидание реакций для выполнения ожидаемых команд по заданным параметрам. Если нужно поставить фильтр на всех пользователей, просто укажите в это опции everyone.
### Использование
```php
$awaitCmdReactions[фильтр;время;реакции;команды;ошибка?;данные?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| фильтр | фильтр пользователей, на которые будет реагировать бот | айди | Да | 
| время | время ожидания бота | время | Да | 
| реакции | реакции на которые бот будет реагировать | перечисление | Да |
| команды | команды, которые бот будет выполнять при реагировании | перечисление | Да |
| ошибка | ошибка, если время ожидания закончилось | текст | Нет |
| данные | данные для ожидаемых команд | объект | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$awaitCmdReactions',
  code: `
$awaitCmdReactions[everyone;10min;:joy:;white_check_mark:;reaction;Ошибка;{}]
})`
```