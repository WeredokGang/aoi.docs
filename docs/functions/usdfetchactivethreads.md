# $fetchActiveThreads
desc
### Использование
```php
$fetchActiveThreads[канал?;...options]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Нет | 
| ...options |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$fetchActiveThreads',
  code: `
$fetchActiveThreads[канал?;...options]`
// Возвращает: ...
})
```
