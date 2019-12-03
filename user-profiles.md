# Users

## https://app-api.pixiv.net/v1/user/detail

Gets information about the specified user.

### Parameters

filter - `for_android`

user_id - e.g. `24970193`

### Example Response

**Parameters**

filter - `for_android`

user_id - `24970193`

**Response**

```json
{
    "user": {
        "id": 24970193,
        "name": "らいふにゃん",
        "account": "catlife72",
        "profile_image_urls": {
            "medium": "https://i.pximg.net/user-profile/img/2018/03/07/09/27/26/13921030_7647eca15abe5f463dfdb820851456c9_170.jpg"
        },
        "comment": "お絵かきするひと～♪♫",
        "is_followed": true
    },
    "profile": {
        "webpage": null,
        "gender": "",
        "birth": "",
        "birth_day": "10-25",
        "birth_year": 0,
        "region": "",
        "address_id": 0,
        "country_code": "",
        "job": "",
        "job_id": 0,
        "total_follow_users": 21,
        "total_mypixiv_users": 0,
        "total_illusts": 27,
        "total_manga": 0,
        "total_novels": 1,
        "total_illust_bookmarks_public": 366,
        "total_illust_series": 0,
        "total_novel_series": 0,
        "background_image_url": null,
        "twitter_account": "life_neko72",
        "twitter_url": "https://twitter.com/life_neko72",
        "pawoo_url": null,
        "is_premium": false,
        "is_using_custom_profile_image": true
    },
    "profile_publicity": {
        "gender": "public",
        "region": "public",
        "birth_day": "public",
        "birth_year": "public",
        "job": "public",
        "pawoo": true
    },
    "workspace": {
        "pc": "",
        "monitor": "",
        "tool": "",
        "scanner": "",
        "tablet": "",
        "mouse": "",
        "printer": "",
        "desktop": "",
        "music": "",
        "desk": "",
        "chair": "",
        "comment": "",
        "workspace_image_url": null
    }
}
```

## https://app-api.pixiv.net/v1/user/illusts

Retrieves a list of the illustrations and manga by the specified user.

### Parameters

filter - `for_android`

user_id - e.g. `24970193`

type - `illust` `manga`

### Example Response

**Parameters**

filter - `for_android`

user_id - `24970193`

type - `illust`

**Response**

```json
{
    "illusts": [
        {
            "id": 77522882,
            "title": "🦉家族みたいにみんな仲良しな話～🐈",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/10/28/17/51/44/77522882_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/28/17/51/44/77522882_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/28/17/51/44/77522882_p0_master1200.jpg"
            },
            "caption": "最近可愛い妹が出来てかばんちゃさんはとっても楽しそうです🎶",
            "restrict": 0,
            "user": {
                "id": 24970193,
                "name": "らいふにゃん",
                "account": "catlife72",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2018/03/07/09/27/26/13921030_7647eca15abe5f463dfdb820851456c9_170.jpg"
                },
                "is_followed": true
            },
            "tags": [
                {
                    "name": "かばんさん",
                    "translated_name": null
                },
                {
                    "name": "サーバル(けものフレンズ)",
                    "translated_name": "Serval (Kemono Friends)"
                },
                {
                    "name": "カラカル(けものフレンズ)",
                    "translated_name": "Caracal (Kemono Friends)"
                },
                {
                    "name": "キュルル(けものフレンズ)",
                    "translated_name": "Kyururu (Kemono Friends)"
                },
                {
                    "name": "ネオかばんちゃん",
                    "translated_name": "Kaban (Kemono Friends Season 2)"
                },
                {
                    "name": "けものフレンズ",
                    "translated_name": "Kemono Friends"
                },
                {
                    "name": "アフリカオオコノハズク(けものフレンズ)",
                    "translated_name": "Northern White-faced Owl (Kemono Friends)"
                },
                {
                    "name": "ワシミミズク(けものフレンズ)",
                    "translated_name": "Eurasian Eagle Owl (Kemono Friends)"
                },
                {
                    "name": "けものフレンズ100users入り",
                    "translated_name": "Kemono Friends 100+ bookmarks"
                }
            ],
            "tools": [],
            "create_date": "2019-10-28T17:51:44+09:00",
            "page_count": 5,
            "width": 848,
            "height": 1200,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {},
            "meta_pages": [
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/10/28/17/51/44/77522882_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/28/17/51/44/77522882_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/28/17/51/44/77522882_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/10/28/17/51/44/77522882_p0.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/10/28/17/51/44/77522882_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/28/17/51/44/77522882_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/28/17/51/44/77522882_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/10/28/17/51/44/77522882_p1.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/10/28/17/51/44/77522882_p2_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/28/17/51/44/77522882_p2_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/28/17/51/44/77522882_p2_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/10/28/17/51/44/77522882_p2.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/10/28/17/51/44/77522882_p3_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/28/17/51/44/77522882_p3_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/28/17/51/44/77522882_p3_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/10/28/17/51/44/77522882_p3.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/10/28/17/51/44/77522882_p4_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/28/17/51/44/77522882_p4_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/28/17/51/44/77522882_p4_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/10/28/17/51/44/77522882_p4.jpg"
                    }
                }
            ],
            "total_view": 4419,
            "total_bookmarks": 320,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false,
            "total_comments": 11
        },
        {
            "etc", "etc"
        }
    ],
    "next_url": null
}
```

## https://app-api.pixiv.net/v1/user/novels

Gets a list of novels from the specified user.

### Parameters

user_id - e.g. `24970193`

### Example Response

**Parameters**

user_id - `24970193`

**Response**

```json
{
    "novels": [
        {
            "id": 9706345,
            "title": "無題",
            "caption": "去年書いた物をブラッシュした、グ(？)←ハな感じのお話。",
            "restrict": 0,
            "x_restrict": 0,
            "is_original": false,
            "image_urls": {
                "square_medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_6_128x128.jpg",
                "medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_6_176mw.jpg",
                "large": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_6_240mw.jpg"
            },
            "create_date": "2018-06-06T22:58:14+09:00",
            "tags": [
                {
                    "name": "グラハウ",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "小説",
                    "translated_name": "novel",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "pkmn腐",
                    "translated_name": "Pokemon BL fanwork",
                    "added_by_uploaded_user": true
                }
            ],
            "page_count": 4,
            "text_length": 6397,
            "user": {
                "id": 24970193,
                "name": "らいふにゃん",
                "account": "catlife72",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2018/03/07/09/27/26/13921030_7647eca15abe5f463dfdb820851456c9_170.jpg"
                },
                "is_followed": true
            },
            "series": {},
            "is_bookmarked": false,
            "total_bookmarks": 17,
            "total_view": 547,
            "visible": true,
            "total_comments": 0,
            "is_muted": false,
            "is_mypixiv_only": false,
            "is_x_restricted": false
        }
    ],
    "next_url": null
}
```

## https://app-api.pixiv.net/v1/user/bookmarks/illust

Retrieves the user's bookarmed illustrations and manga

### Parameters

user_id - e.g. `24970193`

restrict - `public` `private`

### Examples Response

**Parameters**

user_id - `24970193`

restrict - `public`

**Response**

```json
