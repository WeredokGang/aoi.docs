# $channelPermissionsFor
desc
### Использование
```php
$channelPermissionsFor[uorrId?;канал?;sep?;"]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| uorrId |  |  | Нет | 
| канал |  |  | Нет | 
| sep |  |  | Нет |
| " |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$channelPermissionsFor',
  code: `
$channelPermissionsFor[uorrId?;канал?;sep?;"]`
// Возвращает: ...
})
```
