# /histories

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
            "health_status": "Healthy",
            "recommendation": "Good to consume in moderate amounts",
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
            "health_status": "Healthy",
            "recommendation": "Good to consume 1 time per day",
            "createdAt": "2024-11-29T12:58:48.181Z"
        }
    ]
}
```

## GET /histories/{{snackName}}

This API is used to get history by snack name.

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
            "health_status": "Healthy",
            "recommendation": "Good to consume in moderate amounts",
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
            "health_status": "Healthy",
            "recommendation": "Good to consume 1 time per day",
            "createdAt": "2024-11-29T12:58:48.181Z"
        }
    ]
}
```