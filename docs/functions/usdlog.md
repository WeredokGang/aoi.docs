# $log
desc
### Использование
```php
$log[msg]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| msg |  |  | Да |  
## Пример(ы)

```javascript
bot.command({
  name: '$log',
  code: `
$log[msg]`
// Возвращает: ...
})
```