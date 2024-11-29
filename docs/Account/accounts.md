# /accounts

This API is used to verify email.

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