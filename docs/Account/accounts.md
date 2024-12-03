# /accounts

This API is used to verify account.

## POST /accounts

body: 
```
{
    "email": "youremail@gmail.com",
    "verificationCode": "urVerificationCode"
}
```

response:
```
{
    "status": "success",
    "message": "Email successfully verified"
}
```