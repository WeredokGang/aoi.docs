# $roleId
desc
### Использование
```php
$roleId[roleResolver;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roleResolver |  |  | Да | 
| сервер |  |  | Нет | 
## Пример(ы)

```javascript
bot.command({
  name: '$roleId',
  code: `
$roleId[roleResolver;сервер?]`
// Возвращает: ...
})
```
