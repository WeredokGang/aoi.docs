# $isManaged
desc
### Использование
```php
$isManaged[roleId;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleId |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isManaged',
  code: `
$isManaged[roleId;сервер?]`
// Возвращает: ...
})
```
