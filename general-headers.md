# General Headers

Authorization - `Bearer [access token]`
Content-Type `application/x-www-form-urlencoded;charset=UTF-8` (unless multipart)
Host - `oauth.secure.pixiv.net` `app-api.pixiv.net`
Connection - `close`    
Accept-Encoding - `gzip, deflate`
X-Client-Time - RFC3339 converted timestamp
X-Client-Hash - md5([X-Client-Time]+28c1fdd170a5204386cb1313c7077b34f83e4aaf4aa829ce78c231e05b0bae2c)w
