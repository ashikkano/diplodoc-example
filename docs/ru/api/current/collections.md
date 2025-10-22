# Collections

Возвращает актуальную информацию по коллекциям Telegram подарков

### HTTP запрос
```
GET https://api.giftstat.app/current/collections
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
        "api_path": "/current/collections",
    }
}
```


#|
|| Поле | Описание ||
|| id | UInt64 ||
|| str_id | String ||
|| collection | String ||
||

collection_slug

|


||
||

star_price

|


||
||

is_limited

|


||
||

is_sold_out

|


||
||

first_sale_date

|


||
||

last_sale_date

|


||
||

total_amount

|


||
||

issued

|


||
||

minted

|


||
||

non_minted

|


||
||

burned

|


||
||

blockchain_address

|


||
|#

