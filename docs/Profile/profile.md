# /profile

This API is used get profile information.

## GET /

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
    "data": {
        "fullName": "urFullName",
        "username": "urUsername",
        "email": "yourEmail@gmail.com",
        "profilePhoto": "urPhotoUrl"
    }
}

```

