# /register

## POST /register

body:

```
{
    "username": "urUsername",
    "fullName": "Your Full Name",
    "email": "youremail@gmail.com",
    "password": "urPassword",
    "confirmPassword": "urPassword"
}
```

response:
```
{
    "status": "success",
    "message": "Verification code has been sent to email"
}
```