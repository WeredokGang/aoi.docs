# $addApplicationCommandPermissions
Добавляет к аппликации обязательные права для её использования. Если права нужно убрать - укажите право с знаком "-"
### Использование
```php
$addApplicationCommandPermissions[сервер?;аппликация;права]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер | айди сервер на котором нужно добавить права | айди | Нет | 
| аппликация | айди аппликации которую нужно изменить | айди | Да | 
| права | права, которые нужно изменить | перечисление | Да |
## Пример(ы)

```javascript
bot.command({
  name: '$addApplicationCommandPermissions',
  code: `
$addApplicationCommandPermissions[$guildID;972413555930972170;+admin]`
})
```
```javascript
bot.command({
  name: '$addApplicationCommandPermissions',
  code: `
$addApplicationCommandPermissions[$guildID;972413555930972170;-admin]`
})
```
