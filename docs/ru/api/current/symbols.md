# Models

Возвращает узоры Telegram подарков

### HTTP запрос
```
GET https://api.giftstat.app/current/collections/symbols
```

### Path параметры
#|
|| Параметр | Описание ||
|| 
limit 
| 
**UInt**\
Количество элементов в *data*
||

|| 
offset 
| 
**UInt**\
Смещение данных
||
|#


### Структура ответа

HTTP код: 200 - OK

```json
{
    "data": [],
    "meta": {
        "limit": 10000, 
        "offset": 0,
        "count": 0,
        "api_path": "/current/collections/symbols",
    }
}
```


#|
|| Поле | Описание ||
|| id | **UInt** ||
|| str_id | **String** ||
|| collection | **String** ||
|| symbol | **String** ||
|| symbol_slug | **String** ||
|| lower_symbol_slug | **String** ||
|| rarity | **UInt** ||
|#

