# /fullname

This API is used to change fullname.

## PUT /fullname
header:
```
{
    "Authorization": "Bearer urAccessToken"
}
```

body:
```
{
    "fullName": "urNewFullName"
}
```

response:
```
{
    "status": "success",
    "message": "Full name updated successfully",
    "fullName": "urNewFullName",
}
```