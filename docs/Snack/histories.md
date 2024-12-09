# /histories

This API is used to get histories.

## GET /histories

header:
```
{
    "Authorization": "Bearer urAccessToken"
}
```

response
```
{
    "status": "success",
    "data": [
        {
            "snackName": "Chips",
            "nutritions": {
                "fat": 24,
                "saturated_fat": 2,
                "carbohydrates": 40,
                "sugars": 12,
                "fiber": 0,
                "protein": 8,
                "sodium": 0.2
            },
            "health_status": "health status result",
            "recommendation": "recommendation result",
            "createdAt": "2024-11-26T09:47:53.299Z"
        },
        {
            "snackName": "Chips 1",
            "nutritions": {
                "fat": 34,
                "saturated_fat": 2,
                "carbohydrates": 150,
                "sugars": 32,
                "fiber": 0,
                "protein": 8,
                "sodium": 1.5
            },
            "health_status": "health status result",
            "recommendation": "recommendation result"
            "createdAt": "2024-11-29T12:58:48.181Z"
        }
    ]
}
```

## GET /histories/{{snackId}}

This API is used to get history by snack id.

header:
```
{
    "Authorization": "Bearer urAccessToken"
}
```

response:
```
{
    "status": "success",
    "message": "Snack successfully predicted",
    "result": {
        "snackId": "619ef4fffe31b9d8",
        "snackName": "Chips 2",
        "nutritions": {
            "fat": 34,
            "saturated_fat": 2,
            "carbohydrates": 150,
            "sugars": 32,
            "fiber": 0,
            "protein": 8,
            "sodium": 1.5
        },
        "health_status": "health status result",
        "recommendation": "recommendation result"
    }
}

```

## DELETE /histories

header:
```
{
    "Authorization": "Bearer urAccessToken"
}
```

response:
```
    "status": "success",
    "message": "Snack successfully cleared"
```