# $muteUser
desc
### Использование
```php
$muteUser[сервер;userId;mute?;reason]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| userId |  |  | Да | 
| mute |  |  | Нет |
| reason |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$muteUser',
  code: `
$muteUser[сервер;userId;mute?;reason]`
// Возвращает: ...
})
```
