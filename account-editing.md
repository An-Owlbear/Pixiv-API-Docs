# Account Editing

## https://app-api.pixiv.net/v1/user/me/state

Checks the users' current state.

**Requires authorisation header**

**GET request**

### Example Response

```json
{
    "user_state": {
        "is_mail_authorized": true,
        "has_changed_pixiv_id": false,
        "can_change_pixiv_id": true
    }
}
```

## https://app-api.pixiv.net/v1/user/profile/presets

Retrieves the list of presets for countries, locations and jobs.

**GET request**

```json
{
    "profile_presets": {
        "addresses": [
            {
                "id": 1,
                "name": "Hokkaido",
                "is_global": false
            },
            {
                "etc": "etc"
            }
        ],
        "countries": [
            {
                "code": "IS",
                "name": "Iceland"
            },
            {
                "etc": "etc"
            }
        ],
        "jobs": [
            {
                "id": 1,
                "name": "IT"
            },
            {
                "etc": "etc"
            }
        ],
        "default_profile_image_urls": {
            "medium": "https://s.pximg.net/common/images/no_profile.png"
        }
    }
}
```

## https://app-api.pixiv.net/v1/user/profile/edit

Changes the user's information such as username, twitter ID and date of birth.

**Requires authorisation header**

**POST request**

### Parameters

delete_profile_image - `true` `false`
user_name - `[username]`
webpage - `https://www.example.com`
twitter.com - `[twitter id'`
gender - `male` `female` `unknown`
address - `[adress id]`
country - `[country code]`
job - `[job id]`
comment - `[comment]`
gender_publicity - `public` `mypixiv` `private`
address_publicity - `public ` `mypixiv` `private`
birth_year_publicity - `public` `mypixiv` `private`
birth_day_publicity - `public` `mypixiv` `private`
job_publicity - `public` `mypixiv` `private`
pawoo_publicity - `public` `mypixiv` `private`
profile_image - `[image data]`
birthday - `[birth date (yyyy-mm-dd)]` e.g. `2001-07-11`

### Specific Headers

Content-Type - `multipart/form-data boundary=[boundary]`

### Example Response

```json
{}
```
