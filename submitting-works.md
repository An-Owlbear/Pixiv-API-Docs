# Submitting Works

## https://app-api.pixiv.net/v1/upload/illust

Uploads an Illustration, set of illustration or manga with the submitted information.

**Requires authorisation header**

### Specific Headers

Content-Type - `multipart/formdata; boundary=[boundary]`

### Parameters

title - `[title]`

caption - `[caption]`

type = `illust` `manga`

restrict - `public` `mypixiv` `private`

x_restrict - `none` `r18` `r18g`    

is_sexual - `false` `true`

tags[] - `[tags]`

files[] - `[file data]`

### Example Response

**Parameters**

title - `title`

caption - `caption`

type - `illust`

restrict - `public`

x_restrict - `none`

is_sexual - `false`

tags[] - `tag1`

tags[] - `tag2`

files[] - `[file data`

**Response**

```json
{
    "convert_key": "[convert key]"
}
```

## https://app-api.pixiv.net/v1/upload/status

Verifies the status of an upload from the given convert key.

**Requires authorisation header**

### Parameters

convert_key - `[convery key]`

### Example Response

**Parameters**

convert_key - `[convert key]`

**Response**

```json
{
    "illust_id": 123456,
    "status": "COMPLETE"
}
```

## https://app-api.pixiv.net/v1/illust/delete

Deletes the user's work of the specified id.

**Requires authorisation header**

### Parameters

illust_id - `[illust id]`

### Example Response

**Parameters**

illust_id - `[illust id]`

**Response**

```json
{}
```

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
