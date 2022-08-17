# $endif
Завершает блок с $if: "v4"
### Использование
```php
$endif
```

## Пример(ы)

```javascript
bot.command({
  name: '$endif',
  $if: 'v4',
  code: `$if[1==1]
  Да.
$endif`
// Возвращает: Да.
})
```
