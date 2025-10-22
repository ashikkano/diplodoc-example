# Thematics Lines

Возвращает актуальный список подборок линий

### HTTP запрос
```
GET https://api.giftstat.app/current/thematics/lines
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
        "api_path": "/current/thematics/lines",
    }
}
```


#|
|| Поле | Описание ||
|| thematic | **String** ||
|| line | **Array** ||
|#

