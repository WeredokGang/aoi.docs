# $createObject
Создаёт JSON-Объект для подальшего взаимодействия с ним
### Использование
```php
$createObject[данные]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| данные | данные для объекта | объект | Да |  
## Пример(ы)

```javascript
bot.command({
  name: '$createObject',
  code: `$getObjectProperty[hi]
$createObject[{ "hi": "bye" }]`
// Возвращает: bye
})
```
