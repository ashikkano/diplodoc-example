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
        "api_path": "/current/collections",
    }
}
```


#|
|| Поле | Описание ||
|| id | **UInt** ||
|| str_id | **String** ||
|| collection | **String** ||
|| collection_slug | **String** ||
|| star_price | **UInt** ||
|| is_limited | **Bool** ||
|| is_sold_out | **Bool** ||
|| first_sale_date | **DateTime** ||
|| last_sale_date | **DateTime** ||
|| total_amount | **UInt** ||
|| issued | **UInt** ||
|| minted | **UInt** ||
|| non_minted | **UInt** ||
|| burned | **UInt** ||
|| blockchain_address | **String** ||
|#

