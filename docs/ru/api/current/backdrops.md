# Models

Возвращает фоны Telegram подарков

### HTTP запрос
```
GET https://api.giftstat.app/current/collections/backdrops
```

### Query параметры
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
        "api_path": "/current/collections/backdrops",
    }
}
```


#|
|| Поле | Описание ||
|| id | **UInt** ||
|| str_id | **String** ||
|| collection | **String** ||
|| backdrop | **String** ||
|| backdrop_slug | **String** ||
|| lower_backdrop_slug | **String** ||
|| rarity | **UInt** ||
|#

