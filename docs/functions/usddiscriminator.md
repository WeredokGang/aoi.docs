# $discriminator
Возвращает тег пользователя
### Использование
```php
$discriminator[пользователь?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| пользователь | пользователь, тег которого нужно получить | айди | Нет |  
## Пример(ы)

```javascript
bot.command({
  name: '$discriminator',
  code: `
$discriminator[$authorId]`
// Возвращает: 4565
})
```
