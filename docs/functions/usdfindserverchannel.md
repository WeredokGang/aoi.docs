# $findServerChannel
desc
### Использование
```php
$findServerChannel[channelResolver;returnSelf?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| channelResolver |  |  | Да | 
| returnSelf |  |  | Нет | 
| сервер |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$findServerChannel',
  code: `
$findServerChannel[channelResolver;returnSelf?;сервер?]`
// Возвращает: ...
})
```
