# $createApplicationCommand
desc
### Использование
```php
$createApplicationCommand[сервер;name;description;defaultPermission?;type?;...opts]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| name |  |  | Да | 
| description |  |  | Да |
| defaultPermission |  |  | Нет |
| type |  |  | Нет |
| ...opts |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$createApplicationCommand',
  code: `
$createApplicationCommand[сервер;name;description;defaultPermission?;type?;...opts]`
// Возвращает: ...
})
```
