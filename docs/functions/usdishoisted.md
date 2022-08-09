# $isHoisted
desc
### Использование
```php
$isHoisted[roleId;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleId |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isHoisted',
  code: `
$isHoisted[roleId;сервер?]`
// Возвращает: ...
})
```
