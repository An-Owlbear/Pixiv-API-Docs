# Login

## https://oauth.secure.pixiv.net/auth/token

Requests a login token from the server using login details or a refresh token.

### Parameters

client_id - `MOBrBDS8blbauoSck0ZfDbtuzpyT`

client_secret - `lsACyCD94FhDUtGTXi3QzcFE2uU1hqtDaKeqrdwj`

grant_type - `password` `refresh_token`

username (only when signing in) - `[Your username]`

password (only used when signing in) - `[Your password]`

refresh_token (after login) - `[Your refresh token`]

device_token - `pixiv` (on first login) `[your device token]` (when using refresh token)

secure_url - `true` `false`

inclulde_policy - `true` `false`

### Example Response (sign in)

**Parameters**

client_id - `MOBrBDS8blbauoSck0ZfDbtuzpyT`

client_secret - `lsACyCD94FhDUtGTXi3QzcFE2uU1hqtDaKeqrdwj`

grant_type - `password`

username - `[username]`

password - `[password]`

device_token - `pixiv`

secure_url - `true`

include_policy - `true`

**Response**

```json
{
    "response": {
        "access_token": "[your_access_token]",
        "expires_in": 3600,
        "token_type": "bearer",
        "scope": "",
        "refresh_token": "[your_refresh_token]",
        "user": {
            "profile_image_urls": {
                "px_16x16": "https://s.pximg.net/common/images/no_profile_ss.png",
                "px_50x50": "https://s.pximg.net/common/images/no_profile_s.png",
                "px_170x170": "https://s.pximg.net/common/images/no_profile.png"
            },
            "id": "123456",
            "name": "Username",
            "account": "user_123456",
            "mail_address": "mail@example.com",
            "is_premium": false,
            "x_restrict": 0,
            "is_mail_authorized": true,
            "require_policy_agreement": false
        },
        "device_token": "[your_device_token]"
    }
}
```

### Example Reponse (Refreshing Login)

**Parameters**

client_id - `MOBrBDS8blbauoSck0ZfDbtuzpyT`

client_secret - `lsACyCD94FhDUtGTXi3QzcFE2uU1hqtDaKeqrdwj`

grant_type - `refresh_token`

refresh_token - `[refresh token]`

device_token - `[device token]`

secure_url - `true`

include_policy - `true`

**Response**

```json
{
    "response": {
        "access_token": "[your_access_token]",
        "expires_in": 3600,
        "token_type": "bearer",
        "scope": "",
        "refresh_token": "[your_refresh_token]",
        "user": {
            "profile_image_urls": {
                "px_16x16": "https:\\/\\/s.pximg.net\\/common\\/images\\/no_profile_ss.png",
                "px_50x50": "https:\\/\\/s.pximg.net\\/common\\/images\\/no_profile_s.png",
                "px_170x170": "https:\\/\\/s.pximg.net\\/common\\/images\\/no_profile.png"
            },
            "id": "123456",
            "name": "username",
            "account": "user_123456",
            "mail_address": "mail@example.com",
            "is_premium": false,
            "x_restrict": 0,
            "is_mail_authorized": true,
            "require_policy_agreement": false
        },
        "device_token": "[your_device_token]"
    }
}
```
