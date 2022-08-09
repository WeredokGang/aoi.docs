# $userLeaderBoard
desc
### Использование
```php
$userLeaderBoard[сервер;variable;type?;custom?;list?;page?;table?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| variable |  |  | Да | 
| type |  |  | Нет |
| custom |  |  | Нет |
| list |  |  | Нет |
| page |  |  | Нет |
| table |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$userLeaderBoard',
  code: `
$userLeaderBoard[сервер;variable;type?;custom?;list?;page?;table?]`
// Возвращает: ...
})
```
