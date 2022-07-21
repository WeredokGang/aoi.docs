# $allChannelsCount
Выдаёт количество каналов на сервере
### Использование
```php
$allChannelsCount[тип?]
```

### Опции

| Опция | Описание | Тип | Обязательно |
|--------|-------------|------|----------|
| тип | тип каналов, количество которых бот выдаст | текст | Да |  

### Доступные типы каналов
- Voice - Голосовой канал
- Text - Текстовый канал 
- Announcements - Текстовый канал для объявлений
- Stage - Трибуна
- Thread - Ветка

## Пример(ы)

```javascript
bot.command({
  name: '$allChannelsCount',
  code: `
$allChannelsCount[Text]`
// Возвращает: 24
})
```