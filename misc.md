# Miscellaneous

## https://app-api.pixiv.net/v1/emoji

Retrieves json containing a list of emojis, their names, id and urls.

**GET request**

### Example response:

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

**GET request**

### Example reponse:

```json
{
    "illusts": [
        {
            "id": 59031459,
            "title": "聲の形",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2016/09/17/21/50/08/59031459_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2016/09/17/21/50/08/59031459_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2016/09/17/21/50/08/59031459_p0_master1200.jpg"
            },
            "caption": "早速観てきました。後半特にボロボロ泣いちゃいました。<br />音と映像のマッチングが素晴らしいので、是非映画館で観てほしい作品でした。",
            "restrict": 0,
            "user": {
                "id": 73837,
                "name": "モゲラッタ",
                "account": "chroichi",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2010/12/03/13/00/51/2471854_775a3756e90cb5c84dea6c3a032d3169_170.png"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "聲の形",
                    "translated_name": "A Silent Voice"
                },
                {
                    "name": "西宮硝子",
                    "translated_name": "Shouko Nishimiya"
                },
                {
                    "name": "ふつくしい",
                    "translated_name": "beautiful"
                },
                {
                    "name": "聲の形10000users入り",
                    "translated_name": null
                }
            ],
            "tools": [],
            "create_date": "2016-09-17T21:50:08+09:00",
            "page_count": 1,
            "width": 579,
            "height": 818,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {
                "original_image_url": "https://i.pximg.net/img-original/img/2016/09/17/21/50/08/59031459_p0.jpg"
            },
            "meta_pages": [],
            "total_view": 100097,
            "total_bookmarks": 14039,
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

## https://app-api.pixiv.net/v1/notification/user/register

Regestres the user's time zone so they can get notificatons.

**POST request**

### Parameters

timezone_offset
disable_notifications - `true` `false`
