# General Headers

Authorization - `Bearer [access token]`<br>
Content-Type `application/x-www-form-urlencoded;charset=UTF-8` (unless multipart)<br>
Host - `oauth.secure.pixiv.net` `app-api.pixiv.net`<br>
Connection - `close`<br>
Accept-Encoding - `gzip, deflate`<br>
X-Client-Time - RFC3339 converted timestamp<br>
X-Client-Hash - md5([X-Client-Time]+28c1fdd170a5204386cb1313c7077b34f83e4aaf4aa829ce78c231e05b0bae2c)<br>
