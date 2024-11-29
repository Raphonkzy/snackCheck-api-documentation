# /predicts

## POST /predicts
header:
```
{
    "Authorization": "Bearer urAccessToken"
}
```

body:
```
{
  "snackName": "Chips 1",
  "nutritions": {
    "fat": 34,
    "saturated_fat": 2,
    "carbohydrates": 150,
    "sugars": 32,
    "fiber": 0,
    "protein": 8,
    "sodium": 1.5
  }
}
```

response:
```
{
    "status": "success",
    "message": "Snack successfully predicted",
    "result": {
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
    }
}
```