# $leaveThread
desc
### Использование
```php
$leaveThread[канал;threadId]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| threadId |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$leaveThread',
  code: `
$leaveThread[канал;threadId]`
// Возвращает: ...
})
```
