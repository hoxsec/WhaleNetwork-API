# WhaleNetwork API to JSON

## WhaleNetwork API List: 
#### https://www.whale-network.nl/api/v1/users
#### https://www.whale-network.nl/api/v1/friends
#### https://www.whale-network.nl/api/v1/posts
#### https://www.whale-network.nl/api/v1/sponsor
#### https://www.whale-network.nl/api/v1/users
#### https://www.whale-network.nl/api/v1/stats 


## api/v1/users
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
## api/v1/friends
```json
[
    {
        "id": "62",
        "from": "4",
        "to": "4",
        "status": "0"
    },
    {
        "id": "76",
        "from": "4",
        "to": "8",
        "status": "0"
    }
]
```

## api/v1/posts
```json
[
    {
        "id": "1",
        "by_user": "99",
        "date": "2017-04-24 12:13:30"
    }
]
```

## api/v1/sponsor
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

## api/v1/users
```json
[
    {
        "id": "4",
        "name": "Umit Baris Canbolat",
        "username": "hoxsec",
        "email": "umitgame@live.nl",
        "gender": "unlisted",
        "img": "https:\/\/i.imgur.com\/BBGuAne.jpg",
        "b_img": "https:\/\/i.imgur.com\/ob0Nq4u.jpg",
        "rank": "1"
    },
    {
        "id": "8",
        "name": "Whale-BOT",
        "username": "Whale-BOT",
        "email": "support@whale-network.nl",
        "gender": "bot",
        "img": "https:\/\/scontent-ams3-1.xx.fbcdn.net\/v\/t1.0-9\/18118912_148043595732282_5231918157751674839_n.jpg?oh=ea84c2002735154449726323743d0890&oe=5989D47D",
        "b_img": "https:\/\/i.imgur.com\/tHwO7Rl.jpg",
        "rank": "0"
    },
    {
        "id": "16",
        "name": "",
        "username": "",
        "email": "",
        "gender": "unlisted",
        "img": "..\/assets\/img\/gender\/female.png",
        "b_img": "..\/assets\/img\/gender\/b_img.jpg",
        "rank": "0"
    }
]
```

## api/v1/stats
```json
[
    {
        "id": "1",
        "user_id": "4",
        "friends": "0",
        "likes": "0",
        "posts": "7"
    },
    {
        "id": "6",
        "user_id": "8",
        "friends": "0",
        "likes": "0",
        "posts": "1"
    }
]
```


## Please refer to [Whale-Network API](https://www.whale-network.nl/) for the full API documentation.
