# 

# Submitting Works

## https://app-api.pixiv.net/v1/upload/illust

Uploads an Illustration, set of illustration or manga with the submitted information.

**Requires authorisation header**

**POST request**

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

**POST request**

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

## https://app-api.pixiv.net/v1/illust/comment/add

Adds a comment to the specified illustration or comment.

**Requires authorisation header**

**POST request**

### Parameters

illust_id - `[illust_id]`    

commnt - `[comment contents]`

parent_comment_id - `[parent comment]` (if replying)

### Example Response

**Parameters**

illust_id - `[illust id]`

comment - `comment`

**Response**

```json
{
    "comment": {
        "id": 96614177,
        "comment": "comment",
        "date": "2020-01-27T20:00:03+09:00",
        "user": {
            "id": 46124003,
            "name": "[account]",
            "account": "[account]",
            "profile_image_urls": {
                "medium": "https://s.pximg.net/common/images/no_profile.png"
            }
        },
        "has_replies": false
    }
}
```

## https://app-api.pixiv.net/v1/illust/comment/delete

Deletes the specififed comment.

**Requires authorisation header**

**POST request**

### Parameters

comment_id - `[comment_id]`

### Example Response

**Parameters**

comment_id - `[comment_id]`

**Response**

```json
{}
```

## https://app-api.pixiv.net/v1/upload/novel/covers

Retrieves a list of novel covers to use.

**Requires authorisation header**

**GET request**

### Example Response

```json
{
    "covers": [
        {
            "id": 0,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_m.jpg"
        },
        {
            "id": 1,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_1_m.jpg"
        },
        {
            "id": 2,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_2_m.jpg"
        },
        {
            "id": 3,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_3_m.jpg"
        },
        {
            "id": 4,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_4_m.jpg"
        },
        {
            "id": 5,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_5_m.jpg"
        },
        {
            "id": 6,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_6_m.jpg"
        },
        {
            "id": 7,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_7_m.jpg"
        },
        {
            "id": 8,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_8_m.jpg"
        },
        {
            "id": 9,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_9_m.jpg"
        },
        {
            "id": 10,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_10_m.jpg"
        },
        {
            "id": 11,
            "image_url": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_11_m.jpg"
        }
    ]
}
```

## https://app-api.pixiv.net/v1/upload/novel/draft

Uploads a draft of a novel.

**Requires authorisation header**

**POST request**

### Parameters

title - `[title]`

caption - `[caption]`

cover_id - `0` ... `11`

text - `[text]`

restrict - `public` `mypixiv` `private`

x_restrict - `none` `r18` `r18g`

tags[] - `tags`

is_original - `0` `1`

## Example Response

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
    "novel_draft_id": 82868
}
```

## https://app-api.pixiv.net/v1/user/novel-draft-previews

Retrieves a list of the user's drafts.

**Requires authorisation header**

**GET request**

### Example Response

```json
{
    "novel_draft_previews": [
        {
            "novel_draft_id": 82868,
            "title": "test",
            "shortened_text": "test",
            "update_date": "2020-01-09T22:59:29+09:00"
        }
    ],
    "next_url": null
}
```

## https://app-api.pixiv.net/v1/user/novel/draft/detail

Retrieves a draft of a novel of the given ID.

**Requires authorisation header**

**GET request**

### Parameters

draft_id - `[draft_id`]

### Example Response

**Parameters**

draft_id - `[draft_id]`

**Response**

```json
{
    "novel_draft": {
        "novel_draft_id": 82868,
        "title": "test",
        "caption": "test",
        "text": "test",
        "restrict": "private",
        "x_restrict": "none",
        "cover_id": 2,
        "is_original": 1,
        "tags": [
            "test"
        ],
        "update_date": "2020-01-09T22:59:29+09:00",
        "custom_cover_image_url": null
    }
}
```

## https://app-api.pixiv.net/v1/user/novel/draft/delete

Deletes the specified novel draft.

**Requires authorisation header**

**POST request**

### Parameters

draft_id - `[draft_id]`

### Example Response

**Parameters**

draft_id - `[draft_id]`

**Response**

```json
{}
```

## https://app-api.pixiv.net/v1/upload/novel

Submits a novels from the user's input.

**Requires authorisation header**

**POST request**

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

## https://app-api.pixiv.net/v1/novel/delete

Deletes a novel of the specified id.

**Requires authorisation header**

**POST requets**

### Parameters

novel_id - `[novel id]`

### Example Response

**Parameters**

novel_id - `[novel_id]`

**Response**

```json
{}
```

## https://app-api.pixiv.net/v1/novel/comment/add

Adds a comment to the specified novel or comment.

**Requires authorisation header**

**POST request**

### Parameters

novel_id - `[novel_id]`

comment - `[comment]`

parent_comment - `[parent comment`] (if replying)

### Example Response

**Parameters**

novel_id - `[novel_id`]

comment - `comment`

**Response**

```json
{
    "comment": {
        "id": 24316191,
        "comment": "comment",
        "date": "2020-01-27T20:18:00+09:00",
        "user": {
            "id": 46124003,
            "name": "[user]",
            "account": "[user]",
            "profile_image_urls": {
                "medium": "https://s.pximg.net/common/images/no_profile.png"
            }
        },
        "has_replies": false
    }
}
```

## https://app-api.pixiv.net/v1/novel/comment/delete

Deletes the specified comment.

**Requires authorisation header**

**POST request**

### Parameters

comment_id - `[comment_id]`

### Example Response

**Parameters**

comment_id - `[comment id`]

**Response**

```json
{}
```
