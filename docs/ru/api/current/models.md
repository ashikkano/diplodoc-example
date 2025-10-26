# Models

Возвращает модели Telegram подарков

### HTTP запрос
```
GET https://api.giftstat.app/current/collections/models
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
        "api_path": "/current/collections/models",
    }
}
```


#|
|| Поле | Описание ||
|| id | **UInt** ||
|| str_id | **String** ||
|| collection | **String** ||
|| collection_slug | **String** ||
|| model | **String** ||
|| model_slug | **String** ||
|| rarity | **UInt** ||
|#

