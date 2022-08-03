# $createObject
desc
### Использование
```php
$createObject[data]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| data |  |  | Да |  
## Пример(ы)

```javascript
bot.command({
  name: '$createObject',
  code: `
$createObject[data]`
// Возвращает: ...
})
```