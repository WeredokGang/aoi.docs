# $serverChannelExists
desc
### Использование
```php
$serverChannelExists[channel;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| channel |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$serverChannelExists',
  code: `
$serverChannelExists[channel;сервер?]`
// Возвращает: ...
})
```
