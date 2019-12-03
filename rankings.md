# Rankings

## https://app-api.pixiv.net/v1/illust/ranking

Retrieves a list of ranking illusts/manga based on specified parameters.

**Requires authorisation header**

### Parameters

filter -  `for_android`

mode - `day` `week` `month` `day_male` `day_female` `week_original` `week_rookie` `day_manga` `week_rookie_manga` `week_manga` `month_manga`

date - e.g. `2019-11-27` `2017-05-25`

### Example Response

**Parameters**

filter - `for_android`

mode - `day`

**Response**

```json
{
    "illusts": [
        {
            "id": 78010987,
            "title": "花灯恋慕",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/11/27/00/04/09/78010987_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/11/27/00/04/09/78010987_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/11/27/00/04/09/78010987_p0_master1200.jpg"
            },
            "caption": "初出：K-BOOKS プレミアムジークレーNo.333",
            "restrict": 0,
            "user": {
                "id": 27517,
                "name": "藤原",
                "account": "fuzichoco",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2008/03/31/01/13/19/95581_886b0c6eadefd9d6df6a6776a015920d_170.jpg"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "オリジナル",
                    "translated_name": "original"
                },
                {
                    "name": "女の子",
                    "translated_name": "girl"
                },
                {
                    "name": "オリジナル10000users入り",
                    "translated_name": "original 10000+ bookmarks"
                },
                {
                    "name": "チャイナドレス",
                    "translated_name": "China dress"
                },
                {
                    "name": "インナーカラー",
                    "translated_name": "inner color"
                }
            ],
            "tools": [
                "openCanvas"
            ],
            "create_date": "2019-11-27T00:04:09+09:00",
            "page_count": 1,
            "width": 495,
            "height": 700,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {
                "original_image_url": "https://i.pximg.net/img-original/img/2019/11/27/00/04/09/78010987_p0.png"
            },
            "meta_pages": [],
            "total_view": 76847,
            "total_bookmarks": 18126,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": "https://app-api.pixiv.net/v1/illust/ranking?filter=for_android&mode=day&offset=30"
}
```

## https://app-api.pixiv.net/v1/novel/ranking

Retrieves a list of ranking novels based on the specified parameters

**Requires authorisation header**

### Parameters

mode - `day` `week` `day_male` `day_female` `week_rookie`

date - e.g. `2019-11-07`

### Example Response

**Parameters**

mode - `day`

**Response**

```json
{
    "novels": [
        {
            "id": 12006445,
            "title": "鈴木朋子でございます！",
            "caption": "この人の成り代わり夢を見たことないので書いてみました。想像以上に楽しかったです。<br />鈴木朋子さんです。<br />園子ちゃんのお母さんに成り代わり。<br />原作崩壊、色々救済、キッド災難につき、地雷の人は注意してください。",
            "restrict": 0,
            "x_restrict": 0,
            "is_original": false,
            "image_urls": {
                "square_medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_7_128x128.jpg",
                "medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_7_176mw.jpg",
                "large": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_7_240mw.jpg"
            },
            "create_date": "2019-11-27T11:29:08+09:00",
            "tags": [
                {
                    "name": "コナン夢",
                    "translated_name": "ConanYume",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "成り代わり",
                    "translated_name": "original character replacing canon character",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "鈴木財閥",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "原作崩壊",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "なにこれ素敵",
                    "translated_name": "this is lovely",
                    "added_by_uploaded_user": false
                },
                {
                    "name": "続きを全力で待機!",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "シリーズ化希望",
                    "translated_name": "hoping for a series",
                    "added_by_uploaded_user": false
                },
                {
                    "name": "かっこよすぎる…!!",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "理想の女性…!",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "なにこれ新鮮",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                }
            ],
            "page_count": 7,
            "text_length": 26642,
            "user": {
                "id": 1649518,
                "name": "江葉",
                "account": "mirai-3",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2016/03/25/23/07/14/10714103_a77e0d8dc4da227cc829ca0e80b9e04f_170.jpg"
                },
                "is_followed": false
            },
            "series": {},
            "is_bookmarked": false,
            "total_bookmarks": 3518,
            "total_view": 21661,
            "visible": true,
            "total_comments": 87,
            "is_muted": false,
            "is_mypixiv_only": false,
            "is_x_restricted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": "https://app-api.pixiv.net/v1/novel/ranking?mode=day&offset=30"
}
```
