# $cloneChannel
Клонирукт указанный канал
### Использование
```php
$cloneChannel[канал?;название;вернутьАйди?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал | канал, который нужно клонировать | айди | Нет | 
| название | название нового канала | текст | Да | 
| вернутьАйди | вернуть ли айди нового канала | логическое выражение | Нет |
## Пример(ы)

```javascript
bot.command({
  name: '$cloneChannel',
  code: `
$cloneChannel[$channelId;$channelName;yes]`
// Возвращает: 9826371929376270
})
```
