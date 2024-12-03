# /token

This API is used to get a new accessToken from refresh token.

## POST /token

body:
```
{
    "refreshToken": "urRefreshToken"
}
```

response:
```
{
    "status": "success",
    "accessToken": "urNewAccessToken"
}
```