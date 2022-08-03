# $jsonRequest
desc
### Использование
```php
$jsonRequest[link;property?;error;...heads]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| link |  |  | Да | 
| property |  |  | Нет | 
| error |  |  | Да |
| ...heads |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$jsonRequest',
  code: `
$jsonRequest[link;property?;error;...heads]`
// Возвращает: ...
})
```