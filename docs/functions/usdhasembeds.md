# $hasEmbeds
desc
### Использование
```php
$hasEmbeds[messageId?;канал?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| messageId |  |  | Нет | 
| канал |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$hasEmbeds',
  code: `
$hasEmbeds[messageId?;канал?]`
// Возвращает: ...
})
```
