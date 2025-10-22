# Collections

Возвращает актуальную информацию по моделям Telegram подарков

### HTTP запрос
```
GET https://api.giftstat.app/current/collections/models/stat
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
        "limit": 200, 
        "offset": 0,
        "count": 0,
        "api_path": "/current/collections/models/stat",
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
|| rarity | ||
|| model_count | ||
|| total_amount | ||
|| model_share | ||
|#

