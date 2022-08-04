# $deleteApplicationCommand
desc
### Использование
```php
$deleteApplicationCommand[сервер;id]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| id |  |  | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$deleteApplicationCommand',
  code: `
$deleteApplicationCommand[сервер;id]`
// Возвращает: ...
})
```
