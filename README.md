# nodejs-auth
This a a nodejs auth api, based on some social medias like tiktok, here are some basic intructions to send requests:

```
'/api/auth/register'
Method: Post
Data:
  {
    "username":"username",
    "DisplayName":"User name",
    "email":"email@email.com",
    "password":"password123"
}
```

Should return:
```
{
  user: {
    "uuid":"(uuid)"
    "username":"username",
    "DisplayName":"User name",
    "email":"email@email.com"
  }
}
```
