# $createStageInstance
desc
### Использование
```php
$createStageInstance[канал;topic;privacy?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал |  |  | Да | 
| topic |  |  | Да | 
| privacy |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$createStageInstance',
  code: `
$createStageInstance[канал;topic;privacy?]`
// Возвращает: ...
})
```
