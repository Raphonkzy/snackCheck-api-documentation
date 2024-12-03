# /logout

This API is used to logout.

## POST /logout

header:
```
{
    "Authorization":"Bearer urAccessToken"
}
```

body:
```
{
    "username": "urUsername"
}
```

response:
```
{
    "status": "success",
    "message": "Logout successful"
}
```