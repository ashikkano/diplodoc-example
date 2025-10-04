# Current Collections

Возвращает актуальную информацию по коллекциям Telegram подарков


### HTTP request
```
GET https://api.giftstat.app/current/collections
```

### Path parameters


### Response

HTTP code: 200 - OK

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
|| Field | Description ||

|| id | 
 **UInt** 
||

|| str_id |
 **String** 
||

|| collection |
 **String** 
||

|| collection_slug |
 **String** 
||

|| star_price |
 **String** 
||

|| is_limited

|


||
|| is_sold_out

|


||
|| first_sale_date

|


||
|| last_sale_date

|


||
|| total_amount

|


||
|| issued

|


||
|| minted

|


||
|| non_minted

|


||
|| burned

|


||
|| blockchain_address

|


||
|#

