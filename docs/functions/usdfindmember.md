# $findMember
desc
### Использование
```php
$findMember[memberResolver;returnSelf?;сервер?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| memberResolver |  |  | Да | 
| returnSelf |  |  | Нет | 
| сервер |  |  | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$findMember',
  code: `
$findMember[memberResolver;returnSelf?;сервер?]`
// Возвращает: ...
})
```
