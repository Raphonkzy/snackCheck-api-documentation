# /predict

This API is used to predict using original ML-API.

body:
```
{
  "snackName": "Chips",
  "nutritions": {
    "fat": 49,
    "saturated_fat": 2,
    "carbohydrates": 40,
    "sugars": 30,
    "fiber": 0,
    "protein": 12,
    "sodium": 1.5
  }
}
```

response:
```
{
    "categories": {
        "carbohydrates": "5",
        "fat": "5",
        "fiber": "1",
        "proteins": "4",
        "saturated_fat": "2",
        "sodium": "5",
        "sugars": "5"
    },
    "health_status": "Healthy",
    "recommendation": "Good to consume in moderate amounts"
}
```