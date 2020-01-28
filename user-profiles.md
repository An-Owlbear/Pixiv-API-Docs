# Users

## https://app-api.pixiv.net/v1/user/detail

Gets information about the specified user.

**Requires authorisation header**

**GET request**

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

## https://app-api.pixiv.net/v1/user/follow/add

Follows the specified user.

**Requires authorisation header**

**POST request**

### Parameters

user_id - `[user id]`

restrict - `public` `private`

### Example Response

**Parameters**

user_id - `[user id]`

restrict - `public`

**Reponse**

```json
{}
```

## https://app-api.pixiv.net/v1/user/follow/delete

Stops following the specified user.

**Requires authorisaton header**

**POST request**

### Parameters

user_id - `[user id]`

### Example Response

```json
{}
```

## https://app-api.pixiv.net/v1/user/illusts

Retrieves a list of the illustrations and manga by the specified user.

**Requires authorisation header**

**GET request**

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
            "etc": "etc"
        }
    ],
    "next_url": null
}
```

## https://app-api.pixiv.net/v1/user/novels

Gets a list of novels from the specified user.

**Requires authorisation header**

**GET request**

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

**Requires authorisation header**

**GET request**

### Parameters

user_id - e.g. `123456`

restrict - `public` `private`

### Examples Response

**Parameters**

user_id - `[user id]`

restrict - `public`

**Response**

```json
{
    "illusts": [
        {
            "id": 77923918,
            "title": "マホイップちゃん",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/11/21/22/00/29/77923918_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/11/21/22/00/29/77923918_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/11/21/22/00/29/77923918_p0_master1200.jpg"
            },
            "caption": "好き",
            "restrict": 0,
            "user": {
                "id": 40341319,
                "name": "藤依しの",
                "account": "fujii-shino",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2019/11/14/09/03/49/16540073_10773c6ca1b9dc5b48f4b118a08c10fd_170.jpg"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "マホイップ",
                    "translated_name": "Alcremie"
                },
                {
                    "name": "ポケモン擬人化",
                    "translated_name": "pokemon personification"
                },
                {
                    "name": "ポケモン",
                    "translated_name": "Pokémon"
                },
                {
                    "name": "ポケモン剣盾",
                    "translated_name": "Pokémon Sword and Shield"
                }
            ],
            "tools": [],
            "create_date": "2019-11-21T22:00:29+09:00",
            "page_count": 1,
            "width": 1794,
            "height": 2384,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {
                "original_image_url": "https://i.pximg.net/img-original/img/2019/11/21/22/00/29/77923918_p0.jpg"
            },
            "meta_pages": [],
            "total_view": 10148,
            "total_bookmarks": 2148,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": "https://app-api.pixiv.net/v1/user/bookmarks/illust?user_id=24970193&restrict=public&max_bookmark_id=6638389887"
}
```

## https://app-api.pixiv.net/v1/user/bookmarks/novel

Retrieves a list of the specified user's bookmarked novels.

**Requires authorisation header**

**GET request**

### Parameters

user_id - `4599056`

restrict - `public` `private`

### Example Response

https://app-api.pixiv.net/v1/user/mypixiv?filter=for_android&user_id=4599056**Parameters**

user_id - `[user id]`

restrict - `public`

**Response**

```json
{
    "novels": [
        {
            "id": 9703231,
            "title": "起源馳せる",
            "caption": "・ウェルト氏のオリフレ「ネアンデルタール人」(<strong><a href=\"pixiv://illusts/68994961\">illust/68994961</a></strong>)×自作キャラのマリアンです。<br />　知能キャラ同士、頭のよさそうな会話をさせようとして、微妙に纏まらなかった気もする。",
            "restrict": 0,
            "x_restrict": 0,
            "is_original": false,
            "image_urls": {
                "square_medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_4_128x128.jpg",
                "medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_4_176mw.jpg",
                "large": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_4_240mw.jpg"
            },
            "create_date": "2018-06-06T00:40:44+09:00",
            "tags": [
                {
                    "name": "けものフレンズ",
                    "translated_name": "Kemono Friends",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "マリアン",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "ネアンデルタール人(オリフレ)",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "三次創作",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                }
            ],
            "page_count": 1,
            "text_length": 1901,
            "user": {
                "id": 15499610,
                "name": "図書記架",
                "account": "tosyokika",
                "profile_image_urls": {
                    "medium": "https://s.pximg.net/common/images/no_profile.png"
                },
                "is_followed": false
            },
            "series": {},
            "is_bookmarked": false,
            "total_bookmarks": 2,
            "total_view": 193,
            "visible": true,
            "total_comments": 2,
            "is_muted": false,
            "is_mypixiv_only": false,
            "is_x_restricted": false
        }
    ],
    "next_url": "https://app-api.pixiv.net/v1/user/bookmarks/novel?user_id=4599056&restrict=public&max_bookmark_id=535297535"
}
```

## https://app-api.pixiv.net/v1/user/follower

Retrieves a list of followers of the user signed in, this is the case regardless of the user_id provided.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`

user_id - e.g. `123456`

### Example Response

**Parameters**

filter - `for_android`

user_id - `[user id]`

**Response**

```json
{
  "user_previews": [
    {
      "user": {
        "id": 42094327,
        "name": "ろんや",
        "account": "user_rzrh7237",
        "profile_image_urls": {
          "medium": "https://i.pximg.net/user-profile/img/2019/11/20/20/01/58/16564604_e9ce58d3d24c115b785deda765a4d665_170.jpg"
        },
        "is_followed": false
      },
      "illusts": [
        {
          "id": 77897831,
          "title": "賢者と聖母の拾い子はかく祝う",
          "type": "manga",
          "image_urls": {
            "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/11/19/23/45/28/77897831_p0_square1200.jpg",
            "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/11/19/23/45/28/77897831_p0_master1200.jpg",
            "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/11/19/23/45/28/77897831_p0_master1200.jpg"
          },
          "caption": "サーかばが「人と動物”コンビのアニメキャラといえば？ 」ランキング3位入りのお祝い。<br /><br />やはり、この二人は素敵なコンビだ。二人の絆は永遠…決して廃れない輝きをもっている。決して別れたりしない。<br />呪詛から生まれた祝福の子が後の開拓者となるイエイヌ達を救ったように、かざりちゃんにその事を証明するような子に、二人の命綱になって欲しいって思うんだ。<br /><br />サーかばはずっとトゥギャザー!<br />けものフレンズはフォーエバー!",
          "restrict": 0,
          "user": {
            "id": 42094327,
            "name": "ろんや",
            "account": "user_rzrh7237",
            "profile_image_urls": {
              "medium": "https://i.pximg.net/user-profile/img/2019/11/20/20/01/58/16564604_e9ce58d3d24c115b785deda765a4d665_170.jpg"
            },
            "is_followed": false
          },
          "tags": [
            {
              "name": "漫画",
              "translated_name": "manga"
            },
            {
              "name": "けものフレンズ",
              "translated_name": "Kemono Friends"
            },
            {
              "name": "かばんちゃん",
              "translated_name": "Kaban-chan"
            },
            {
              "name": "サーバル(けものフレンズ)",
              "translated_name": "Serval (Kemono Friends)"
            },
            {
              "name": "サーかば",
              "translated_name": null
            },
            {
              "name": "サーバルちゃん",
              "translated_name": "Serval-chan"
            },
            {
              "name": "かざりちゃん",
              "translated_name": null
            }
          ],
          "tools": [],
          "create_date": "2019-11-19T23:45:28+09:00",
          "page_count": 1,
          "width": 834,
          "height": 1177,
          "sanity_level": 2,
          "x_restrict": 0,
          "series": null,
          "meta_single_page": {
            "original_image_url": "https://i.pximg.net/img-original/img/2019/11/19/23/45/28/77897831_p0.jpg"
          },
          "meta_pages": [],
          "total_view": 375,
          "total_bookmarks": 13,
          "is_bookmarked": true,
          "visible": true,
          "is_muted": false
        },
        {
          "etc": "etc"
        }
      ],
      "is_muted": false
    },
    {
      "etc": "etc"
    }
  ],
  "next_url": null
}
```

## https://app-api.pixiv.net/v1/user/following

Retrieves a list of users followed by the specified account.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`

user_id - e.g. `123456`

restrict - `public`

### Example Response

```json
{
    "user_previews": [
        {
            "user": {
                "id": 38525559,
                "name": "うさぺんぎん",
                "account": "user_wnwz5258",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2019/03/23/01/01/24/15555099_aa6da9e3599b0d6363deb9a3481ee37b_170.png"
                },
                "is_followed": true
            },
            "illusts": [
                {
                    "id": 78142063,
                    "title": "炭治郎と 禰豆子ちゃん",
                    "type": "illust",
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/12/05/00/00/07/78142063_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/12/05/00/00/07/78142063_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/12/05/00/00/07/78142063_p0_master1200.jpg"
                    },
                    "caption": "炭治郎と<br />禰豆子ちゃん描いてみました！",
                    "restrict": 0,
                    "user": {
                        "id": 38525559,
                        "name": "うさぺんぎん",
                        "account": "user_wnwz5258",
                        "profile_image_urls": {
                            "medium": "https://i.pximg.net/user-profile/img/2019/03/23/01/01/24/15555099_aa6da9e3599b0d6363deb9a3481ee37b_170.png"
                        },
                        "is_followed": true
                    },
                    "tags": [
                        {
                            "name": "鬼滅の刃",
                            "translated_name": "Demon Slayer: Kimetsu no Yaiba"
                        },
                        {
                            "name": "炭治郎",
                            "translated_name": null
                        },
                        {
                            "name": "禰豆子",
                            "translated_name": "Nezuko Kamado"
                        },
                        {
                            "name": "竈門炭治郎",
                            "translated_name": "Tanjirou Kamado"
                        },
                        {
                            "name": "竈門禰豆子",
                            "translated_name": "Nezuko Kamado"
                        }
                    ],
                    "tools": [],
                    "create_date": "2019-12-05T00:00:07+09:00",
                    "page_count": 1,
                    "width": 1000,
                    "height": 716,
                    "sanity_level": 2,
                    "x_restrict": 0,
                    "series": null,
                    "meta_single_page": {
                        "original_image_url": "https://i.pximg.net/img-original/img/2019/12/05/00/00/07/78142063_p0.png"
                    },
                    "meta_pages": [],
                    "total_view": 209,
                    "total_bookmarks": 19,
                    "is_bookmarked": false,
                    "visible": true,
                    "is_muted": false
                },
                {
                    "etc": "etc"
                }
            ],
            "is_muted": "false"
        },
    ],
    "next_url": "https://app-api.pixiv.net/v1/user/following?filter=for_android&user_id=30249784&restrict=public&offset=30"
}
```

## https://app-api.pixiv.net/v1/user/mypixiv

Retrieves a list of users from the specified user's my pixiv list.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`

user_id - e.g. `123456`

### Example Response

**Parameters**

filter - `for_android`

user_id - `[user id]`

**Response**

```json
{
    "user_previews": [
        {
            "user": {
                "id": 9114625,
                "name": "ぎわしー",
                "account": "flameyossi77",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2015/07/06/14/52/18/9580333_9ccf07389ce2ac2e1c154aaefe4a67f9_170.jpg"
                },
                "is_followed": false
            },
            "illusts": [
                {
                    "id": 60388955,
                    "title": "こちさなー",
                    "type": "illust",
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2016/12/15/20/37/09/60388955_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2016/12/15/20/37/09/60388955_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2016/12/15/20/37/09/60388955_p0_master1200.jpg"
                    },
                    "caption": "早苗ちゃんかわいいよbotが精製した、新しい早苗ちゃんです。<br />おへそが風になびいて露わになっているところがポイントです。<br /><br />どうでもいいんですけど、早苗ちゃんのこと早苗さんって呼ぶと別のゲームの人物が引っかかるんで早苗ちゃんって呼ぼうよみんな",
                    "restrict": 0,
                    "user": {
                        "id": 9114625,
                        "name": "ぎわしー",
                        "account": "flameyossi77",
                        "profile_image_urls": {
                            "medium": "https://i.pximg.net/user-profile/img/2015/07/06/14/52/18/9580333_9ccf07389ce2ac2e1c154aaefe4a67f9_170.jpg"
                        },
                        "is_followed": false
                    },
                    "tags": [
                        {
                            "name": "ふつくしい",
                            "translated_name": "beautiful"
                        },
                        {
                            "name": "早苗さん",
                            "translated_name": null
                        },
                        {
                            "name": "早苗ちゃん",
                            "translated_name": null
                        },
                        {
                            "name": "早苗ちゃんかわいいよ",
                            "translated_name": null
                        },
                        {
                            "name": "けしからん",
                            "translated_name": "shameless"
                        },
                        {
                            "name": "おへそ",
                            "translated_name": "bellybutton"
                        },
                        {
                            "name": "東風谷早苗",
                            "translated_name": "sanae kochiya"
                        },
                        {
                            "name": "東方",
                            "translated_name": "Touhou"
                        },
                        {
                            "name": "自演タグ",
                            "translated_name": null
                        },
                        {
                            "name": "自演乙",
                            "translated_name": null
                        }
                    ],
                    "tools": [],
                    "create_date": "2016-12-15T20:37:09+09:00",
                    "page_count": 1,
                    "width": 2381,
                    "height": 3177,
                    "sanity_level": 2,
                    "x_restrict": 0,
                    "series": null,
                    "meta_single_page": {
                        "original_image_url": "https://i.pximg.net/img-original/img/2016/12/15/20/37/09/60388955_p0.jpg"
                    },
                    "meta_pages": [],
                    "total_view": 2705,
                    "total_bookmarks": 6,
                    "is_bookmarked": false,
                    "visible": true,
                    "is_muted": false
                },
                {
                    "id": 55124939,
                    "title": "……アンチョビじゃない…ちよみって呼んで。",
                    "type": "illust",
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2016/02/06/18/17/04/55124939_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2016/02/06/18/17/04/55124939_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2016/02/06/18/17/04/55124939_p0_master1200.jpg"
                    },
                    "caption": "酒の席で盛り上がった奴を描き起こしました。誰か続き描いてください。",
                    "restrict": 0,
                    "user": {
                        "id": 9114625,
                        "name": "ぎわしー",
                        "account": "flameyossi77",
                        "profile_image_urls": {
                            "medium": "https://i.pximg.net/user-profile/img/2015/07/06/14/52/18/9580333_9ccf07389ce2ac2e1c154aaefe4a67f9_170.jpg"
                        },
                        "is_followed": false
                    },
                    "tags": [
                        {
                            "name": "安斎千代美",
                            "translated_name": null
                        },
                        {
                            "name": "ガールズアンドパンツァー",
                            "translated_name": null
                        },
                        {
                            "name": "アンチョビ",
                            "translated_name": "Anchovy"
                        },
                        {
                            "name": "ガルパン",
                            "translated_name": "Girls und Panzer"
                        },
                        {
                            "name": "ガールズ&パンツァー",
                            "translated_name": "Girls und Panzer"
                        }
                    ],
                    "tools": [],
                    "create_date": "2016-02-06T18:17:04+09:00",
                    "page_count": 1,
                    "width": 945,
                    "height": 1024,
                    "sanity_level": 2,
                    "x_restrict": 0,
                    "series": null,
                    "meta_single_page": {
                        "original_image_url": "https://i.pximg.net/img-original/img/2016/02/06/18/17/04/55124939_p0.jpg"
                    },
                    "meta_pages": [],
                    "total_view": 826,
                    "total_bookmarks": 1,
                    "is_bookmarked": false,
                    "visible": true,
                    "is_muted": false
                },
                {
                    "id": 55115509,
                    "title": "車をぶつけました。",
                    "type": "illust",
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2016/02/06/02/48/37/55115509_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2016/02/06/02/48/37/55115509_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2016/02/06/02/48/37/55115509_p0_master1200.jpg"
                    },
                    "caption": "運転席のドアが傷まみれです。修理代考えたくない。",
                    "restrict": 0,
                    "user": {
                        "id": 9114625,
                        "name": "ぎわしー",
                        "account": "flameyossi77",
                        "profile_image_urls": {
                            "medium": "https://i.pximg.net/user-profile/img/2015/07/06/14/52/18/9580333_9ccf07389ce2ac2e1c154aaefe4a67f9_170.jpg"
                        },
                        "is_followed": false
                    },
                    "tags": [
                        {
                            "name": "レイプ目みぽりん",
                            "translated_name": null
                        },
                        {
                            "name": "みぽりん",
                            "translated_name": null
                        },
                        {
                            "name": "西住みほ",
                            "translated_name": "Miho Nishizumi"
                        },
                        {
                            "name": "ガルパン",
                            "translated_name": "Girls und Panzer"
                        },
                        {
                            "name": "ガールズアンドパンツァー",
                            "translated_name": null
                        },
                        {
                            "name": "ガールズ&パンツァー",
                            "translated_name": "Girls und Panzer"
                        }
                    ],
                    "tools": [],
                    "create_date": "2016-02-06T02:48:37+09:00",
                    "page_count": 1,
                    "width": 1023,
                    "height": 888,
                    "sanity_level": 2,
                    "x_restrict": 0,
                    "series": null,
                    "meta_single_page": {
                        "original_image_url": "https://i.pximg.net/img-original/img/2016/02/06/02/48/37/55115509_p0.jpg"
                    },
                    "meta_pages": [],
                    "total_view": 1733,
                    "total_bookmarks": 2,
                    "is_bookmarked": false,
                    "visible": true,
                    "is_muted": false
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
