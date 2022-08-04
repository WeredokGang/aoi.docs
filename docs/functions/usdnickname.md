# $nickname
desc
### Использование
```php
$nickname[userId?;сервер?;returnUser?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
| returnUser |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$nickname',
  code: `
$nickname[userId?;сервер?;returnUser?]`
// Возвращает: ...
})
```
