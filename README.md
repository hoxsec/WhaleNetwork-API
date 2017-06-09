# WhaleNetwork API to JSON

WhaleNetwork API List: 
api/v1/users
api/v1/friends
api/v1/posts
api/v1/sponsor
api/v1/users
api/v1/stats


api/v1/users
```json
[
    {
        "id": "99", 
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
        "by_user": "99",
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
        "button": "1",
        "button_link": "##", 
        "button_text": "##",
        "image": "##"
    }
]
```

Please refer to [Whale-Network API](https://www.whale-network.nl/) for the full API documentation.
