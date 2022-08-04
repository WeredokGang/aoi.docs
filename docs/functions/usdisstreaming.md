# $isStreaming
desc
### Использование
```php
$isStreaming[userId?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| userId |  |  | Нет | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$isStreaming',
  code: `
$isStreaming[userId?;сервер?]`
// Возвращает: ...
})
```
