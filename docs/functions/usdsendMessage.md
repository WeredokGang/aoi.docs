# $sendMessage
desc
### Использование
```php
$sendMessage[message;returnId?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| message |  |  | Да | 
| returnId |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$sendMessage',
  code: `
$sendMessage[message;returnId?]`
// Возвращает: ...
})
```