# Pre Login

## https://app-api.pixiv.net/v1/emoji
Retrieves json containing a list of emojis, their names, id and urls.

**Example response:**

```json
{
    "emoji_definitions": [
        {
            "id": 101,
            "slug": "normal",
            "image_url_medium": "https://s.pximg.net/common/images/emoji/128x128/101_128x128.png"
        },
        {
            "id": 102,
            "slug": "surprise",
            "image_url_medium": "https://s.pximg.net/common/images/emoji/128x128/102_128x128.png"
        },
        {
            "id": 103,
            "slug": "serious",
            "image_url_medium": "https://s.pximg.net/common/images/emoji/128x128/103_128x128.png"
        },
        {
            "etc": "etc"
        }
    ]
}
```

## https://app-api.pixiv.net/v1/walkthrough/illusts
Retrieves a list of images to show to a new user.

**Example reponse:**
```json
{
    "illusts": [
        {
            "id": 50688289,
            "title": "マフィアμ's",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2015/06/02/19/39/27/50688289_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2015/06/02/19/39/27/50688289_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2015/06/02/19/39/27/50688289_p0_master1200.jpg"
            },
            "caption": "",
            "restrict": 0,
            "user": {
                "id": 5038059,
                "name": "sizuka",
                "account": "sizuka0",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2013/10/18/13/44/38/6951485_93f599f06b5d60047ed22cdf1b031e8d_170.jpg"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "ラブライブ!",
                    "translated_name": "love live!"
                },
                {
                    "name": "μ's",
                    "translated_name": null
                },
                {
                    "name": "マフィアパロ",
                    "translated_name": null
                },
                {
                    "name": "なにこれかっこいい",
                    "translated_name": "so cool!"
                },
                {
                    "name": "スーツ",
                    "translated_name": "suit"
                },
                {
                    "name": "勝てる気がしない",
                    "translated_name": "feels like we can't win"
                },
                {
                    "name": "ことりちゃんのゲス顔",
                    "translated_name": null
                },
                {
                    "name": "ラブライブ!30000users入り",
                    "translated_name": null
                },
                {
                    "name": "ラブライブ!10000users入り",
                    "translated_name": "Love Live! 10000+ bookmarks"
                },
                {
                    "name": "おっぱいのついたイケメン",
                    "translated_name": "hot guy with boobs"
                }
            ],
            "tools": [
                "SAI"
            ],
            "create_date": "2015-06-02T19:39:27+09:00",
            "page_count": 1,
            "width": 3000,
            "height": 1920,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {
                "original_image_url": "https://i.pximg.net/img-original/img/2015/06/02/19/39/27/50688289_p0.jpg"
            },
            "meta_pages": [],
            "total_view": 432489,
            "total_bookmarks": 33055,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url":null
}
```
