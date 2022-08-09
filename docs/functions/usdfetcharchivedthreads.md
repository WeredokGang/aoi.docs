# $fetchArchivedThreads
desc
### Использование
```php
$fetchArchivedThreads[канал?;...options]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Нет | 
| ...options |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$fetchArchivedThreads',
  code: `
$fetchArchivedThreads[канал?;...options]`
// Возвращает: ...
})
```
