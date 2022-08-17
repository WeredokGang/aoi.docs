# $deleteApplicationCommand
Удаляет аппликационную команду (слэш) на указанном сервере
### Использование
```php
$deleteApplicationCommand[сервер;аппликация]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер | сервер или global где нужно удалить аппликацию | айди | Да | 
| аппликация | аппликация которую нужно удалить | айди | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$deleteApplicationCommand',
  code: `
$deleteApplicationCommand[$guildId;$getApplicationCommandId[$message[1];$guildId]]`
})
```
