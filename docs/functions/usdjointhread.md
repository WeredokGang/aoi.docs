# $joinThread
desc
### Использование
```php
$joinThread[канал;threadId]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| threadId |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$joinThread',
  code: `
$joinThread[канал;threadId]`
// Возвращает: ...
})
```
