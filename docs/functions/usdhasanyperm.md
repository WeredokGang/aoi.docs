# $hasAnyPerm
desc
### Использование
```php
$hasAnyPerm[сервер;userId;...perms]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер |  |  | Да | 
| userId |  |  | Да | 
| ...perms |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$hasAnyPerm',
  code: `
$hasAnyPerm[сервер;userId;...perms]`
// Возвращает: ...
})
```
