# $deleteMessage
desc
### Использование
```php
$deleteMessage[сообщение;channel?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сообщение |  |  | Да | 
| channel |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$deleteMessage',
  code: `
$deleteMessage[сообщение;channel?]`
// Возвращает: ...
})
```
