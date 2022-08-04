# $deleteThread
desc
### Использование
```php
$deleteThread[канал;threadId;reason]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| threadId |  |  | Да | 
| reason |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$deleteThread',
  code: `
$deleteThread[канал;threadId;reason]`
// Возвращает: ...
})
```
