# $createChannelInvite
Создаёт ссылку-приглашение для заданного канала с указанными опциями в виде объекта во второй опции
### Использование
```php
$createChannelInvite[канал?;...опции]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| канал | канал, для которого нужно создать ссылку-приглашение | айди | Нет | 
| ...опции | опции приглашения | объект | Да | 
## Пример(ы)

```javascript
bot.command({
  name: '$createChannelInvite',
  code: `
$createChannelInvite[$channelId;{
  "maxUses": "1"
}]`
// Возвращает: https://discord.gg/Hg4PQWL8K7
})
```
