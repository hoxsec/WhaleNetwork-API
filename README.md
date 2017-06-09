# JSON API with PHP/MySQL
PHP/MySQL API JSON Encode

WhaleNetwork API List: 

api/v1/users
```json
[
    {
        "id": "99", <-- id from DB
        "name": "HOXSEC",
        "username": "HOXSEC",
        "email": "example@mail.com",
        "gender": "male",
        "img": "##",
        "b_img": "##",
        "rank": "#"
    }
]
```
api/v1/posts
```json
[
    {
        "id": "1",
        "by_user": "99", <-- user id from posts
        "date": "2017-04-24 12:13:30"
    }
]
```
api/v1/sponsor
```json
[
    {
        "id": "1",
        "user_id": "99",
        "title_text": "##",
        "info_text": "##",
        "button": "1", <-- either 1 or 0.
        "button_link": "##", 
        "button_text": "##",
        "image": "##"
    }
]
```

Please refer to [Whale-Network API](https://www.whale-network.nl/) for the full API documentation.
