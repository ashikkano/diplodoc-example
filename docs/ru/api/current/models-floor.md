# Collections

Возвращает актуальную информацию по флору моделей Telegram подарков

### HTTP запрос
```
GET https://api.giftstat.app/current/collections/models/floor
```

### Path параметры
#|
|| Параметр | Описание ||
|| 
limit 
| 
**UInt64**\
Количество элементов в *data*
||

|| 
offset 
| 
**UInt64**\
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
        "api_path": "/current/collections/models/floor",
    }
}
```


#|
|| Поле | Описание ||
|| id | UInt64 ||
|| str_id | String ||
|| collection | String ||
|| collection_slug | ||
|| model | ||
|| model_slug | ||
|| floor_price | ||
|#

