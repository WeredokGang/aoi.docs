# $loopMode
desc
### Использование
```php
$loopMode[mode?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| mode |  |  | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$loopMode',
  code: `
$loopMode[mode?]`
// Возвращает: ...
})
```