# $createServerInvite
Создаёт ссылку-приглашение для сервера
### Использование
```php
$createServerInvite[сервер?;...опции]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| сервер | сервер, на котором нужно создать ссылку-приглашение | айди | Нет | 
| ...опции | опции приглашения | объект | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$createServerInvite',
  code: `
$createServerInvite[$guildId;{
  "maxUses": "10"
  }]`
// Возвращает: https://discord.gg/KpF0LPBhj2XD
})
```
