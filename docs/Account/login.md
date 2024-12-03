# /login

This API is used to login.

## POST /login

body:

```
{
    "username": "urUsername",
    "password": "urPassword"
}
```

response:
```
{
    "status": "success",
    "message": "Login successsful",
    "accessToken": "urAccessToken",
    "refreshToken": "urRefreshToken"
}
```