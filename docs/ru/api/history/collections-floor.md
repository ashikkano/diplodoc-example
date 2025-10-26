# Collections Floor

Возвращает актуальный флор по коллекциям Telegram подарков

### HTTP запрос
```
GET https://api.giftstat.app/collections/history/floor
```

### Query параметры
#|
|| Параметр | Описание ||
|| 
marketplace
| 
**String**\
- portals (default)
- tonnel
- getgems
||
|| 
scale
| 
**String**\
- day (default)
- hour
||
|| 
days
| 
**UInt**
||
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
        "limit": 200, 
        "offset": 0,
        "count": 0,
        "api_path": "/history/collections/floor",
    }
}
```


#|
|| Поле | Описание ||
|| id | **UInt** ||
|| str_id | **String** ||
|| collection | **String** ||
|| collection_slug | **String** ||
|| lower_slug | **String** ||
|| floor_price | **Float** ||
|| marketplace | **String** ||
|#


