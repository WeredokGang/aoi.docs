# $editIn
Изменяет отправленное сообщение после указанного времени на указанн(ое, ые) новое сообщение
### Использование
```php
$editIn[время;...сообщения]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| время | время, через которое изменится сообщение | время | Да | 
| ...сообщения | новые сообщения, на которые изменится сообщение через указанное время | перечисление | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$editIn',
  code: `
$editIn[3s;...сообщение;...ещё сообщение;...и ещё]
Привет, мир!`
// Возвращает: Привет, мир! > ...сообщение > ...ещё сообщение > ...и ещё
})
```
