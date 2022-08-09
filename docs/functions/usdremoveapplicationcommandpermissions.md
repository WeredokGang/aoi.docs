# $removeApplicationCommandPermissions
desc
### Использование
```php
$removeApplicationCommandPermissions[сервер?;id;...roruids]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| id |  |  | Да | 
| ...roruids |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$removeApplicationCommandPermissions',
  code: `
$removeApplicationCommandPermissions[сервер?;id;...roruids]`
// Возвращает: ...
})
```
