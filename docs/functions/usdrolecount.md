# $roleCount
desc
### Использование
```php
$roleCount[сервер?;fetchFirst?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет | 
| fetchFirst |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$roleCount',
  code: `
$roleCount[сервер?;fetchFirst?]`
// Возвращает: ...
})
```
