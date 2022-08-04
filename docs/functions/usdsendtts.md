# $sendTTS
desc
### Использование
```php
$sendTTS[канал;message;returnId?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| message |  |  | Да | 
| returnId |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$sendTTS',
  code: `
$sendTTS[канал;message;returnId?]`
// Возвращает: ...
})
```
