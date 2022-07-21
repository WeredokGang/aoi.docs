# $awaitData
Получает данные с объекта данных в ожидаемой команды.
### Использование
```php
$awaitData[свойство]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| свойство | свойство, которое нужно получить из объекта данных | текст | Да |  
## Пример(ы)

```javascript
bot.command({
  name: '$awaitData',
  code: `
$awaitData[hi]
$loop[1;{ "hi": "bye" };gn]`
  //Возвращает: bye
})
```