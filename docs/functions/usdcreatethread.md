# $createThread
desc
### Использование
```php
$createThread[канал;name;archive?;type?;startMessage;returnId?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| name |  |  | Да | 
| archive |  |  | Нет |
| type |  |  | Нет |
| startMessage |  |  | Да |
| returnId |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$createThread',
  code: `
$createThread[канал;name;archive?;type?;startMessage;returnId?]`
// Возвращает: ...
})
```
