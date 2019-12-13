# Submitting Works

## https://app-api.pixiv.net/v1/upload/novel

Submits a novels from the user's input.

**Requires authorisation header**

### Parameters

title - `[title]`

caption - `[caption]`

cover_id  - `0` ... `11`

text - `[text]`

restrict - `public` `mypixiv` `private`

x_restrict `none` `r18` `r18g`

tags[] - `[tags]`

is_original - `0` `1`

### Example Response

**Parameters**

title - `title`

caption - `caption`

cover_id - `0`

text - `text`

restrict - `public`

x_restrict - `none`

tags[] - `tag1`

tags[] - `tag2`

is_original - `0`

**Response**

```json
{
    "novel_id": 1234567
}
```


