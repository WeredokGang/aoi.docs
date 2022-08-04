# $msg
desc
### Использование
```php
$msg[канал?;messageId?;option?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Нет | 
| messageId |  |  | Нет | 
| option |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$msg',
  code: `
$msg[канал?;messageId?;option?]`
// Возвращает: ...
})
```
