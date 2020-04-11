# Search

## https://app-api.pixiv.net/v1/search/illust

Retrieves a list of illustrations from the specified search terms.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`<br>
include_translated_tag_results - `true` `false`<br>
merge_plain_keyword_results - `true` `false`<br>
word - `[word]`<br>
sort - `date_desc` `date_asc`<br>
search_target - `partial_match_for_tags` `exact_match_for_tags` `title_and_caption`<br>
start_date - `[start date]`<br>
end_date - `[end date]`

### Example Response

**Request parameters**

filter - `for_android`<br>
include_translated_tag_results - `true`<br>
merge_plain_keyword_results - `true`<br>
word - `けものフレンズ%20かわいい`<br>
search_target - `partial_match_for_tags`<br>
sort - `date_desc`

**Response**

```json
{
    "illusts": [
        {
            "id": 77398205,
            "title": "その他イラスト",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/10/21/00/24/20/77398205_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/21/00/24/20/77398205_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/21/00/24/20/77398205_p0_master1200.jpg"
            },
            "caption": "TwitterにあげたVTuber以外のイラストです",
            "restrict": 0,
            "user": {
                "id": 15485746,
                "name": "香風まーさ。",
                "account": "tales-0406",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2019/09/09/19/08/20/16257404_4a9b0253152f3e5f3e68bc25de6ee010_170.png"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "魔法少女まどか☆マギカ",
                    "translated_name": "Puella Magi Madoka Magica"
                },
                {
                    "name": "けものフレンズ",
                    "translated_name": "Kemono Friends"
                },
                {
                    "name": "テイルズオブシンフォニア",
                    "translated_name": "tales of symphonia"
                },
                {
                    "name": "キタキツネ(けものフレンズ)",
                    "translated_name": "Ezo Red Fox (Kemono Friends)"
                },
                {
                    "name": "北上(艦隊これくしょん)",
                    "translated_name": "Kitakami (Kantai Collection)"
                },
                {
                    "name": "かわいい",
                    "translated_name": "cute"
                },
                {
                    "name": "艦これ",
                    "translated_name": "Kancolle"
                }
            ],
            "tools": [],
            "create_date": "2019-10-21T00:24:20+09:00",
            "page_count": 4,
            "width": 800,
            "height": 900,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {},
            "meta_pages": [
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/10/21/00/24/20/77398205_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/21/00/24/20/77398205_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/21/00/24/20/77398205_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/10/21/00/24/20/77398205_p0.png"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/10/21/00/24/20/77398205_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/21/00/24/20/77398205_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/21/00/24/20/77398205_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/10/21/00/24/20/77398205_p1.png"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/10/21/00/24/20/77398205_p2_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/21/00/24/20/77398205_p2_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/21/00/24/20/77398205_p2_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/10/21/00/24/20/77398205_p2.png"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/10/21/00/24/20/77398205_p3_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/10/21/00/24/20/77398205_p3_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/10/21/00/24/20/77398205_p3_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/10/21/00/24/20/77398205_p3.png"
                    }
                }
            ],
            "total_view": 542,
            "total_bookmarks": 24,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": "https://app-api.pixiv.net/v1/search/illust?filter=for_android&include_translated_tag_results=true&merge_plain_keyword_results=true&word=%E3%81%91%E3%82%82%E3%81%AE%E3%83%95%E3%83%AC%E3%83%B3%E3%82%BA+%E3%81%8B%E3%82%8F%E3%81%84%E3%81%84&sort=date_desc&search_target=partial_match_for_tags&offset=30",
    "search_span_limit": 31536000
}        
```

## https://app-api.pixiv.net/v1/search/popular-preview/illust

Retrieves a single page of popular illusts

**GET request**

### Parameters

filter - `for_android`<br>
include_translated_tag_results - `true` `false`<br>
merge_plain_keyword_results - `true` `false`<br>
word - `[word]`<br>
sort - `date_desc` `date_asc`<br>
search_target - `partial_match_for_tags` `exact_match_for_tags` `title_and_caption`<br>
start_date - `[start date]`<br>
end_date - `[end date]`

### Example Response

**Request parameters**

filter - `for_android`<br>
include_translated_tag_results - `true`<br>
merge_plain_keyword_results - `true`<br>
word - `先輩がうざい`<br>
search_target - `partial_match_for_tags`

**Response**

```json
{
    "illusts": [
        {
            "id": 65014429,
            "title": "先輩がうざい後輩の話",
            "type": "manga",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2017/09/18/00/34/44/65014429_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2017/09/18/00/34/44/65014429_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2017/09/18/00/34/44/65014429_p0_master1200.jpg"
            },
            "caption": "先輩が飲んでいるのはノンアルです。ご安心をば",
            "restrict": 0,
            "user": {
                "id": 10509347,
                "name": "しろまんた",
                "account": "misomisomiso1020",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2018/04/27/14/31/50/14147053_e9dc153993f26de401c0359022455531_170.jpg"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "創作",
                    "translated_name": "creation"
                },
                {
                    "name": "オリジナル",
                    "translated_name": "original"
                },
                {
                    "name": "なにこれ可愛い",
                    "translated_name": "what is this cuteness"
                },
                {
                    "name": "先輩×後輩",
                    "translated_name": "senpai x kouhai"
                },
                {
                    "name": "プロポーズ",
                    "translated_name": null
                },
                {
                    "name": "伝説の始まり",
                    "translated_name": "the beginning of the legend"
                },
                {
                    "name": "オリジナル漫画",
                    "translated_name": "original comic"
                },
                {
                    "name": "先輩がうざい後輩の話",
                    "translated_name": "My Senpai Is Annoying"
                },
                {
                    "name": "オリジナル30000users入り",
                    "translated_name": "original 30000+ Bookmarks"
                },
                {
                    "name": "ハンドルキーパー",
                    "translated_name": null
                }
            ],
            "tools": [],
            "create_date": "2017-09-18T00:34:44+09:00",
            "page_count": 4,
            "width": 1451,
            "height": 2048,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": {
                "id": 21859,
                "title": "先輩がうざい後輩の話"
            },
            "meta_single_page": {},
            "meta_pages": [
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2017/09/18/00/34/44/65014429_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2017/09/18/00/34/44/65014429_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2017/09/18/00/34/44/65014429_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2017/09/18/00/34/44/65014429_p0.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2017/09/18/00/34/44/65014429_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2017/09/18/00/34/44/65014429_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2017/09/18/00/34/44/65014429_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2017/09/18/00/34/44/65014429_p1.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2017/09/18/00/34/44/65014429_p2_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2017/09/18/00/34/44/65014429_p2_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2017/09/18/00/34/44/65014429_p2_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2017/09/18/00/34/44/65014429_p2.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2017/09/18/00/34/44/65014429_p3_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2017/09/18/00/34/44/65014429_p3_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2017/09/18/00/34/44/65014429_p3_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2017/09/18/00/34/44/65014429_p3.jpg"
                    }
                }
            ],
            "total_view": 1051434,
            "total_bookmarks": 49917,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "search_span_limit": 31536000
}
```

## https://app-api.pixiv.net/v1/search/novel

Retrieves a list of novels from the specified search terms.

**Requires authorisation header.**

**GET request**

### Parameters

include_translated_tag_results - `true` `false`<br>
merge_plain_keyword_results - `true` `false`<br>
word - `[word]`<br>
sort - `date_desc` `date_asc`<br>
search_target - `partial_match_for_tags` `exact_match_for_tags` `title_and_caption`

### Example Response

**Request parameters**

include_translated_tag_results - `true`<br>
merge_plain_keyword_results - `true`<br>
word - `けものフレンズ`<br>
sort - `date_desc`<br>
search_target - `partial_match_for_tags`

**Response**

```json
{
    "novels": [
        {
            "id": 12004262,
            "title": "仮面ライダージオウ アナザーキュルル編 その6",
            "caption": "祝え 仮面ライダーキュルルの誕生を！",
            "restrict": 0,
            "x_restrict": 0,
            "is_original": false,
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/128x128/novel-cover-master/img/2019/11/26/21/20/23/12004262_4d53a290d2080bbdd05b3975925dbe9e_square1200.jpg",
                "medium": "https://i.pximg.net/c/176x352/novel-cover-master/img/2019/11/26/21/20/23/12004262_4d53a290d2080bbdd05b3975925dbe9e_master1200.jpg",
                "large": "https://i.pximg.net/c/240x480_80/novel-cover-master/img/2019/11/26/21/20/23/12004262_4d53a290d2080bbdd05b3975925dbe9e_master1200.jpg"
            },
            "create_date": "2019-11-26T21:20:23+09:00",
            "tags": [
                {
                    "name": "かばんちゃん",
                    "translated_name": "Kaban-chan",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "けものフレンズ",
                    "translated_name": "Kemono Friends",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "けものフレンズ2",
                    "translated_name": "Kemono Friends 2",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "アナザーキュルル",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "キュルル",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "サーバル(けものフレンズ)",
                    "translated_name": "Serval (Kemono Friends)",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "カラカル(けものフレンズ)",
                    "translated_name": "Caracal (Kemono Friends)",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "仮面フレンズ",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                }
            ],
            "page_count": 6,
            "text_length": 13740,
            "user": {
                "id": 4443025,
                "name": "真鍋棒@けものフレンズ3",
                "account": "nodokahasibi6",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2018/10/26/17/06/40/14945708_e4fccdc43c044178cca0aee508a02d49_170.jpg"
                },
                "is_followed": false
            },
            "series": {
                "id": 1152698,
                "title": "仮面ライダージオウ×けものフレンズ"
            },
            "is_bookmarked": false,
            "total_bookmarks": 3,
            "total_view": 82,
            "visible": true,
            "total_comments": 0,
            "is_muted": false,
            "is_mypixiv_only": false,
            "is_x_restricted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": "https://app-api.pixiv.net/v1/search/novel?include_translated_tag_results=true&merge_plain_keyword_results=true&word=%E3%81%91%E3%82%82%E3%81%AE%E3%83%95%E3%83%AC%E3%83%B3%E3%82%BA&sort=date_desc&search_target=partial_match_for_tags&offset=30",
    "search_span_limit": 31536000
}
```

## https://app-api.pixiv.net/v1/search/user

Retrieves a list of users from the specified search terms

**Requires authorisation header.**

**GET request**

### Parameters

filter - `for_android`<br>
word - `[word]`

### Example response

**Request parameters**

filter - `for_android`<br>
word - `らいふ` 

**Response**    

```json
{
    "user_previews": [
        {
            "user": {
                "id": 501469,
                "name": "あめえばらいふ",
                "account": "ameebalife",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2017/02/15/23/33/48/12153396_b4dc7aa87d786b6e44af78a1b6dbb3d2_170.jpg"
                },
                "is_followed": false
            },
            "illusts": [
                {
                    "id": 76938118,
                    "title": "ワンステップスイベカワイイ",
                    "type": "illust",
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/09/23/23/39/13/76938118_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/09/23/23/39/13/76938118_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/09/23/23/39/13/76938118_p0_master1200.jpg"
                    },
                    "caption": "もりくぼとホルモン",
                    "restrict": 0,
                    "user": {
                        "id": 501469,
                        "name": "あめえばらいふ",
                        "account": "ameebalife",
                        "profile_image_urls": {
                            "medium": "https://i.pximg.net/user-profile/img/2017/02/15/23/33/48/12153396_b4dc7aa87d786b6e44af78a1b6dbb3d2_170.jpg"
                        },
                        "is_followed": false
                    },
                    "tags": [
                        {
                            "name": "アイドルマスターシンデレラガールズ",
                            "translated_name": "The Idolmaster: Cinderella Girls"
                        },
                        {
                            "name": "ワンステップス",
                            "translated_name": null
                        },
                        {
                            "name": "森久保乃々",
                            "translated_name": "Nono Morikubo"
                        },
                        {
                            "name": "関裕美",
                            "translated_name": "Hiromi Seki"
                        },
                        {
                            "name": "白菊ほたる",
                            "translated_name": "Hotaru Shiragiku"
                        },
                        {
                            "name": "スターライトステージ",
                            "translated_name": "Starlight Stage"
                        }
                    ],
                    "tools": [
                        "Photoshop",
                        "ComicStudio",
                        "シャープペンシル"
                    ],
                    "create_date": "2019-09-23T23:39:13+09:00",
                    "page_count": 1,
                    "width": 715,
                    "height": 1000,
                    "sanity_level": 2,
                    "x_restrict": 0,
                    "series": null,
                    "meta_single_page": {
                        "original_image_url": "https://i.pximg.net/img-original/img/2019/09/23/23/39/13/76938118_p0.jpg"
                    },
                    "meta_pages": [],
                    "total_view": 3702,
                    "total_bookmarks": 159,
                    "is_bookmarked": false,
                    "visible": true,
                    "is_muted": false
                },
                {
                    "etc": "etc"
                }
            ],
            "novels": [],
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": null
}
```

## https://app-api.pixiv.net/v2/search/autocomplete

Provides potential tags to autocomplete to based on the user's current input.

**Requires authorisation header**

**GET request**

### Parameters

merge_plain_keyword_results - `true` `false`<br>
word  - `[word]`

### Example Response

**Parameters**

merge_plain_keyword_results - `true`<br>
word - `kemono`

**Response**

```json
{
    "tags": [
        {
            "name": "ケモノ",
            "translated_name": null
        },
        {
            "name": "けものフレンズ",
            "translated_name": "Kemono Friends"
        },
        {
            "name": "獣耳",
            "translated_name": null
        },
        {
            "name": "獣",
            "translated_name": null
        },
        {
            "name": "けもの",
            "translated_name": null
        },
        {
            "name": "獸耳",
            "translated_name": null
        },
        {
            "name": "獣娘",
            "translated_name": null
        },
        {
            "name": "けものフレンズ2",
            "translated_name": "Kemono Friends 2"
        },
        {
            "name": "ケモノ耳",
            "translated_name": null
        },
        {
            "name": "獣の楼郭",
            "translated_name": null
        }
    ]
}
```
