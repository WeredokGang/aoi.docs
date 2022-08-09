# $modifyChannelPerms
desc
### Использование
```php
$modifyChannelPerms[roruId;канал;...perms]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| roruId |  |  | Да | 
| канал |  |  | Да | 
| ...perms |  |  | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$modifyChannelPerms',
  code: `
$modifyChannelPerms[roruId;канал;...perms]`
// Возвращает: ...
})
```
