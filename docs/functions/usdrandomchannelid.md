# $randomChannelID
desc
### Использование
```php
$randomChannelID[сервер?;type?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| type |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$randomChannelID',
  code: `
$randomChannelID[сервер?;type?]`
// Возвращает: ...
})
```
