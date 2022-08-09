# $serverBanner
desc
### Использование
```php
$serverBanner[сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$serverBanner',
  code: `
$serverBanner[сервер?]`
// Возвращает: ...
})
```
