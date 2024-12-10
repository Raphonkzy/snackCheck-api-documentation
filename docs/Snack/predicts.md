# /predicts

This API is used to predict a snack.

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
    "result": {
        "snackId": "619ef4fffe31b9d8",
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
        "recommendation": "recommendation result",
        "categories": {
            "carbohydrates": "Very High in carbohydrates",
            "fat": "Very High in fat",
            "fiber": "Very Low in fiber",
            "proteins": "Low in proteins",
            "saturated_fat": "Moderate in saturated fat",
            "sodium": "Very High in sodium",
            "sugars": "Very High in sugars"
        },
        "createdAt": "2024-11-26T09:47:53.299Z"
    }
}
```
