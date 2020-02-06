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

delete_profile_image - `true` `false`<br>
user_name - `[username]`<br>
webpage - `https://www.example.com`<br>
twitter.com - `[twitter id'`<br>
gender - `male` `female` `unknown`<br>
address - `[adress id]`<br>
country - `[country code]`<br>
job - `[job id]`<br>
comment - `[comment]`<br>
gender_publicity - `public` `mypixiv` `private`<br>
address_publicity - `public ` `mypixiv` `private`<br>
birth_year_publicity - `public` `mypixiv` `private`<br>
birth_day_publicity - `public` `mypixiv` `private`<br>
job_publicity - `public` `mypixiv` `private`<br>
pawoo_publicity - `public` `mypixiv` `private`<br>
profile_image - `[image data]`<br>
birthday - `[birth date (yyyy-mm-dd)]` e.g. `2001-07-11`

### Specific Headers

Content-Type - `multipart/form-data boundary=[boundary]`

### Example Response

```json
{}
```
