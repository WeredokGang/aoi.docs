# $hasPerms
desc
### Использование
```php
$hasPerms[сервер;userId;...perms]
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
  name: '$hasPerms',
  code: `
$hasPerms[сервер;userId;...perms]`
// Возвращает: ...
})
```
