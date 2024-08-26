# teleapi
Action: GET<br>
endpoint: type /generatekey on your bot

## Get Stock info
```/getProduk?itemid=&amount=```



Example result
```json
{
    "status": true,
    "message": "Succsesfully Get item From stock",
    "details": {
        "itemName": "Viu Private 1 Tahun FW",
        "itemPrice": 1000,
        "itemDesc": "Warranty 10 month",
        "itemid": 1,
        "amount": 1,
        "total": 100
    },
    "result": [
        "9. 33. shahof@wyith.my.id | viu12345 | 348 Days"
    ]
}
```

## Get Info Bot
```/getInfo```

Example result
```json
{
    "status": true,
    "message": "Berhasil Mendapat detail bot",
    "botConf": {
        "bot_token": " ",
        "owner_chatid": " ",
        "store_name": " ",
        "invoice_logger": " ",
        "owner_usn": " ",
        "stok_chatid": " ",
        "trakteer_depo": " ",
        "enable_custom_scripting": true,
        "port_webhook": "3000",
        "endpoint_callback_trakteer": "secretrareepic",
        "deposit_settings": {
            "only_admin_deposit": false,
            "enabled_trakteer_deposit": false,
            "paymentgateway": true
        },
        "payment_type": {
            "midtrans": false,
            "paydisini": true
        },
        "paydisini_conf": {
            "fee": 1
        },
        "enable_refferal_link": false,
        "ref_conf": {
            "invite": 100,
            "join": 50
        },
        "enable_question_on_start": true,
        "default_user_if_false": {
            "username": "Anonymous",
            "birthday": "01-01-2000"
        },
        "stiker_start_fileid": "CAACAgUAAxkBAAECPLdl9VzgQCKvb0Q73DIiU6qkZ3NtJAACNQoAAq4wYFaIM0H-IASMdTQE",
        "button_menu": {
            "informasi": "🪪 Information",
            "deposit": "💳 Deposit",
            "list": "🛍️ List Produk",
            "stock": "🛒 Stock"
        }
    }
}
```

## Private Dm User
```/sendMessage?chat_id=&message=```

example result
```json
{
    "status": true,
    "message": "Succesfully send message",
    "response": {
        "ok": true,
        "result": {
            "message_id": 12648,
            "from": {
                "id": 6360863408,
                "is_bot": true,
                "first_name": "Aisbir Sense",
                "username": "Aisbircubecheckout_bot"
            },
            "chat": {
                "id": 1550087439,
                "first_name": "Aisbirkoenz chat di wa biar di balas",
                "username": "aisbirkoenz",
                "type": "private"
            },
            "date": 1724688318,
            "text": "hi"
        }
    }
}
```

## Ban User
```/ban?id=```

example result

## unban User
```/ban?id=```

example result
