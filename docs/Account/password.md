# /password

## POST /password
This API is used to forgot password.

body:
```
{
    "email": "youremail@gmail.com"
}
```

response:
```
{
    "status": "success",
    "message": "Password reset code sent successfully"
}
```

## PUT /password
This API is used to reset password.

body:
```
{
  "email": "youremail@gmail.com",
  "resetCode": "urResetCode",
  "newPassword": "urNewPassword",
  "confirmPassword": "confirmUrNewPassword"
}
```

response:
```
{
    "status": "success",
    "message": "Password successfully reset"
}
```