# $randomUserID
desc
### Использование
```php
$randomUserID[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$randomUserID',
  code: `
$randomUserID[сервер?]`
// Возвращает: ...
})
```
