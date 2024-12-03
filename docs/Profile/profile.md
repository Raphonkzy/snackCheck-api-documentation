# /profile

This API is used to update profile picture.

## GET /profile

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
        "profilePhotoUrl": "urProfilePhotoUrl"
    }
}
```

