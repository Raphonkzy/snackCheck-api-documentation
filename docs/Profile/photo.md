# /photo

## POST /photo
This API is used to upload profile picture.

header:
```
{
    "Authorization": "Bearer urAccessToken",
    "Content-Type": "multipart/form-data"
}
```

body:
```
{
    "profilePhoto": "urPhotoFile"
}
```

response:
```
{
    "status": "success",
    "message": "Profile photo uploaded successfully",
    "url": "urProfilePhotoUrl",
}
```

## PUT /photo
This API is used to update profile picture.

header:
```
{
    "Authorization": "Bearer urAccessToken",
    "Content-Type": "multipart/form-data"
}
```

body:
```
{
    "profilePhoto": "urPhotoFile"
}
```

response:
```
{
    "status": "success",
    "message": "Profile photo updated successfully",
    "url": "urProfilePhotoUrl",
}
```
