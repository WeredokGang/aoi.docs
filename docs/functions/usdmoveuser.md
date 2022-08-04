# $moveUser
desc
### Использование
```php
$moveUser[guildId;userId;канал;reason]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| guildId |  |  | Да | 
| userId |  |  | Да | 
| канал |  |  | Да |
| reason |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$moveUser',
  code: `
$moveUser[guildId;userId;канал;reason]`
// Возвращает: ...
})
```
