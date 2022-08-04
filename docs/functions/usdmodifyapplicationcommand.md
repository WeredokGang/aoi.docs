# $modifyApplicationCommand
desc
### Использование
```php
$modifyApplicationCommand[сервер;id;...Datas]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| id |  |  | Да | 
| ...Datas |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$modifyApplicationCommand',
  code: `
$modifyApplicationCommand[сервер;id;...Datas]`
// Возвращает: ...
})
```
