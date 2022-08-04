# $removeThreadMember
desc
### Использование
```php
$removeThreadMember[канал;threadId;userId;reason]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| threadId |  |  | Да | 
| userId |  |  | Да |
| reason |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$removeThreadMember',
  code: `
$removeThreadMember[канал;threadId;userId;reason]`
// Возвращает: ...
})
```
