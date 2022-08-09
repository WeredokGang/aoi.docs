# $deleteSticker
desc
### Использование
```php
$deleteSticker[сервер;sticker]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| sticker |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$deleteSticker',
  code: `
$deleteSticker[сервер;sticker]`
// Возвращает: ...
})
```
