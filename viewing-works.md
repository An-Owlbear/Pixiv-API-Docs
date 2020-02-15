# Viewing Works

## https://app-api.pixiv.net/v1/illust/detail

Retrieves information about the specified Illustration or Manga.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`<br>
illust_id - e.g. `123456`

### Example Response

**Parameters**

filter - `for_android`<br>
illust_id - `78127058`

**Response**

```json
{
    "illust": {
        "id": 78127058,
        "title": "はなのささやき",
        "type": "illust",
        "image_urls": {
            "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/12/04/00/00/06/78127058_p0_square1200.jpg",
            "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/12/04/00/00/06/78127058_p0_master1200.jpg",
            "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/12/04/00/00/06/78127058_p0_master1200.jpg"
        },
        "caption": "",
        "restrict": 0,
        "user": {
            "id": 1023317,
            "name": "gomzi@3日目南ラ-37a",
            "account": "gcmzi",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2019/03/02/02/03/17/15468155_0f8c84cd2988950b2942ac2e59e5ad82_170.png"
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
                "name": "創作",
                "translated_name": "creation"
            },
            {
                "name": "鎖骨",
                "translated_name": "collarbone"
            },
            {
                "name": "ボブカット",
                "translated_name": "boy-cut"
            },
            {
                "name": "ネックレス",
                "translated_name": "necklace"
            },
            {
                "name": "オリジナル10000users入り",
                "translated_name": "original 10000+ bookmarks"
            }
        ],
        "tools": [],
        "create_date": "2019-12-04T00:00:06+09:00",
        "page_count": 1,
        "width": 601,
        "height": 850,
        "sanity_level": 2,
        "x_restrict": 0,
        "series": null,
        "meta_single_page": {
            "original_image_url": "https://i.pximg.net/img-original/img/2019/12/04/00/00/06/78127058_p0.png"
        },
        "meta_pages": [],
        "total_view": 79940,
        "total_bookmarks": 21741,
        "is_bookmarked": false,
        "visible": true,
        "is_muted": false,
        "total_comments": 56
    }
}
```

## https://app-api.pixiv.net/v2/illust/comments

Retrieves for comments on the specified illustration or manga.

**Requires authorisation header**

**GET request**

### Parameters

illust_id -  e.g. `123456`

### Example Response

**Parameters**

illust_id - `78127058`

**Response**

```json
{
    "comments": [
        {
            "id": 94827923,
            "comment": "瞳の透明感がすごいです…！",
            "date": "2019-12-08T18:49:27+09:00",
            "user": {
                "id": 17511,
                "name": "あまりる",
                "account": "amaril",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2007/11/21/23/39/36/32654_8790e6ef4309e449d0c377a3606fc298_170.jpg"
                }
            },
            "has_replies": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": null
}
```

## https://app-api.pixiv.net/v1/illust/comment/replies

Retrieves the replies of the specified comment.

**Requires authorisation header**

**GET request**

### Parameters

comment_id - e.g. `123456`

### Example Response

**Parameters**

comment_id - `94926629`

**Response**

```json
{
    "comments": [
        {
            "id": 94943386,
            "comment": "ん？いまなんでもしまむら着るって言ったよね",
            "date": "2019-12-12T10:08:01+09:00",
            "user": {
                "id": 48868,
                "name": "ウタカタ",
                "account": "Ashley",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2015/12/14/00/51/40/10239979_914c75d57237837088b580b6f7e3a5f4_170.png"
                }
            },
            "has_replies": false
        }
    ],
    "next_url": null
}
```

## https://app-api.pixiv.net/v2/illust/bookmark/add

Adds the specified illustration/manga to the user's bookmarks.

**Requires authorisation header**

**POST request**

### Parameters

illust_id - `[illust id]`<br>
restrict - `public` `private`

### Example Response

**Parameters**

illust_id - `[illust id]`<br>
restrict - `public`

**Response**

```json
{}
```

## https://app-api.pixiv.net/v1/illust/bookmark/delete

Removes the specified illustration/manga from the user's bookmarks

**Requires authorisation header**

**POST request**

### Parameters

illust_id - `[illust id]`

### Example Response

```json
{}
```

## https://app-api.pixiv.net/v2/novel/detail

Retrieves information about the specified novel.

**Requires authorisation header**

**GET request**

### Parameters

novel_id - e.g. `123456`

### Example Response

**Parameters**

novel_id - `12035664`

**Response**

```json
{
    "novel": {
        "id": 12035664,
        "title": "こういうの霊視っていうんですか？7",
        "caption": "書かせていただきました！！すっごい提造です！！すっごいです！今回はすごい沢山の提造があります！お気を付けてください！！<br /><br />コメント、ブクマ、スタンプ、いいねありがとうございます！！<br />何かありましたらツイッターの方にご連絡ください。",
        "restrict": 0,
        "x_restrict": 0,
        "is_original": false,
        "image_urls": {
            "square_medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_10_128x128.jpg",
            "medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_10_176mw.jpg",
            "large": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_10_240mw.jpg"
        },
        "create_date": "2019-12-04T06:28:10+09:00",
        "tags": [
            {
                "name": "鬼滅の夢",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "オリ主",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "女主",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "煉獄杏寿郎",
                "translated_name": "Kyojuro Rengoku",
                "added_by_uploaded_user": true
            },
            {
                "name": "続きを正座待機",
                "translated_name": null,
                "added_by_uploaded_user": false
            },
            {
                "name": "鬼滅の夢小説3000users入り",
                "translated_name": null,
                "added_by_uploaded_user": false
            }
        ],
        "page_count": 4,
        "text_length": 18401,
        "user": {
            "id": 17572202,
            "name": "アジサイ。",
            "account": "kani0522",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2019/10/24/20/09/36/16456615_b78d26e880a843d108d9d4686a8c245a_170.png"
            },
            "is_followed": false
        },
        "series": {
            "id": 1189914,
            "title": "もしかして、見えてますか？"
        },
        "is_bookmarked": false,
        "total_bookmarks": 3541,
        "total_view": 17321,
        "visible": true,
        "total_comments": 62,
        "is_muted": false,
        "is_mypixiv_only": false,
        "is_x_restricted": false
    }
}
```

## https://app-api.pixiv.net/v1/novel/text

Retrieves the text of a novel.

**Requires authorisation header**

**GET request**

### Parameters

novel_id  - `[novel id]`

### Example Response

```json
{
    "novel_marker": {},
    "novel_text": "[Novel text]",
    "series_prev": {
        "id": 12056770,
        "title": "ドラゴンタイプの胃袋を掴んでしまう女の子の話",
        "caption": "パティシエになりたかった女の子とキバナさんのお話。<br />こんなのが書けたらな〜〜と、勢いよく纏めてみました。じりじりと距離を縮めていく二人の出会い編。キバナさん夢というより、フライゴンががっつり出しゃばっています。<br />設定などまだまだツメが甘いので、気になるところがあるかもしれませんが、ご容赦ください。続く……のだろうか。<br /><br />そういえば、アニポケもついにガラルに入りましたね。もうね、シュートシティからいつナックルシティに行くのかどきどきが止まりません。<br />思わぬ沼にはまり胸が苦しいのと、楽しみがたくさん増えて嬉しいこの頃です。<br /><br />（たくさんのいいね、ブクマありがとうございます！タグもめちゃくちゃ嬉しいです！ちなみに、初タグ付けで、思わずニヤニヤの止まらない週末となりました。明日からも頑張ります。ちなみに、ひとまず頭痛持ちシリーズに関しては続編執筆中です。隣に立てないは書くとしたら、監禁ものとかになってしまうかも……）",
        "restrict": 0,
        "x_restrict": 0,
        "is_original": false,
        "image_urls": {
            "square_medium": "https://i.pximg.net/c/128x128/novel-cover-master/img/2019/12/09/01/13/00/12056770_3f9b090778f761787234167c03605802_square1200.jpg",
            "medium": "https://i.pximg.net/c/176x352/novel-cover-master/img/2019/12/09/01/13/00/12056770_3f9b090778f761787234167c03605802_master1200.jpg",
            "large": "https://i.pximg.net/c/240x480_80/novel-cover-master/img/2019/12/09/01/13/00/12056770_3f9b090778f761787234167c03605802_master1200.jpg"
        },
        "create_date": "2019-12-09T01:13:00+09:00",
        "tags": [
            {
                "name": "pkmn夢",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "オリ主",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "キバナ",
                "translated_name": "Raihan",
                "added_by_uploaded_user": true
            },
            {
                "name": "続きを全裸待機!!",
                "translated_name": null,
                "added_by_uploaded_user": false
            },
            {
                "name": "冬の全裸は寒いですね!!(ﾊﾞｯ!",
                "translated_name": null,
                "added_by_uploaded_user": false
            },
            {
                "name": "よしみんなでキャンプをしよう‼︎",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "pkmn夢5000users入り",
                "translated_name": null,
                "added_by_uploaded_user": false
            },
            {
                "name": "飯テロ(スイーツver.)",
                "translated_name": null,
                "added_by_uploaded_user": false
            },
            {
                "name": "pkmn夢小説長編第一話リンク",
                "translated_name": null,
                "added_by_uploaded_user": false
            }
        ],
        "page_count": 5,
        "text_length": 7890,
        "user": {
            "id": 31399358,
            "name": "ミーシア",
            "account": "mmmisia",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2018/07/26/13/38/37/14538072_2674f2235cfc93d072c4edd10d415e64_170.jpg"
            },
            "is_followed": false
        },
        "series": {
            "id": 1218629,
            "title": "パティシエになりたかった女の子の話"
        },
        "is_bookmarked": false,
        "total_bookmarks": 8965,
        "total_view": 56874,
        "visible": true,
        "total_comments": 22,
        "is_muted": false,
        "is_mypixiv_only": false,
        "is_x_restricted": false
    },
    "series_next": {
        "id": 12072582,
        "title": "ドラゴンタイプの胃袋を掴んでしまう女の子の話３",
        "caption": "「ヌメラのねがいぼし」前編<br />キバナさんとキャンプをしよう！の巻。いつものごとく彼の手持ちがでしゃばっておりますが、ヌメラだけは全然懐いてくれません。<br />前作に続き、設定などはゆるゆるのところがありますので軽い気持ちで読んでくださればと思います。<br />ちなみに前作よりかは甘くない。<br />キバナさんはいくらヌメラがぬめぬめしようともたくさん抱っこしてくれる、はず……！<br /><br />そういえば、なんだかすごいことが起こっています。本当に、これは現実……？<br />信じられないのほどのいいね、ブクマ、コメントの数々、ありがとうございます！全裸待機してくださった方々も、心までダイマックスしてしまったあなたも、本当に寒い中お疲れ様でした……！<br />そして、ランキング１位……！いや本当になにが起きてるんだ……。<br />自分の好きを詰め込んだだけのお話が、ここまで読んでいただけるとは思わず、正直動揺を飛び越えて不安になっております。大丈夫ですか？粗相をしていませんか……？<br />本当、キバナさん人気恐るべしですね。一体何人の女を沼に落としたのなるのやら……。<br /><br />とにかく！本当にいつも拙い話を読んでくださるみなさまには、感謝してもしきれません。お疲れのところ、貴重なお時間を割いていただきありがとうございます。<br />これからもしばらく続きますのでどうぞよろしくお願いします。<br /><br />プロットは練ってありますが、勢いで書き上げているので誤字脱字誤用など多々あるかもしれません。なにかありましたら、お手数ですがご一報下さると助かります。",
        "restrict": 0,
        "x_restrict": 0,
        "is_original": false,
        "image_urls": {
            "square_medium": "https://i.pximg.net/c/128x128/novel-cover-master/img/2019/12/13/02/29/22/12072582_5f0764fca4c32e5bfff960776a20a0b9_square1200.jpg",
            "medium": "https://i.pximg.net/c/176x352/novel-cover-master/img/2019/12/13/02/29/22/12072582_5f0764fca4c32e5bfff960776a20a0b9_master1200.jpg",
            "large": "https://i.pximg.net/c/240x480_80/novel-cover-master/img/2019/12/13/02/29/22/12072582_5f0764fca4c32e5bfff960776a20a0b9_master1200.jpg"
        },
        "create_date": "2019-12-13T02:29:22+09:00",
        "tags": [
            {
                "name": "pkmn夢",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "オリ主",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "キバナ",
                "translated_name": "Raihan",
                "added_by_uploaded_user": true
            },
            {
                "name": "これはヌメラ夢といっても過言ではない可愛さ",
                "translated_name": null,
                "added_by_uploaded_user": false
            },
            {
                "name": "続きを全裸待機!",
                "translated_name": null,
                "added_by_uploaded_user": false
            },
            {
                "name": "pkmn夢3000users入り",
                "translated_name": null,
                "added_by_uploaded_user": true
            }
        ],
        "page_count": 5,
        "text_length": 10330,
        "user": {
            "id": 31399358,
            "name": "ミーシア",
            "account": "mmmisia",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2018/07/26/13/38/37/14538072_2674f2235cfc93d072c4edd10d415e64_170.jpg"
            },
            "is_followed": false
        },
        "series": {
            "id": 1218629,
            "title": "パティシエになりたかった女の子の話"
        },
        "is_bookmarked": false,
        "total_bookmarks": 3210,
        "total_view": 37125,
        "visible": true,
        "total_comments": 45,
        "is_muted": false,
        "is_mypixiv_only": false,
        "is_x_restricted": false
    }
}
```

## https://app-api.pixiv.net/v2/novel/comments

Retrieves a list of comments of the specified novel

**Requires authorisation header**

**GET request**

### Parameters

novel_id - e.g. `123456`

### Example Response

**Parameters**

novel_id - `12035664`

**Response**

```json
{
    "comments": [
        {
            "id": 23837421,
            "comment": "何度読んでも泣いちゃいます(´；ω；`)",
            "date": "2019-12-09T11:56:00+09:00",
            "user": {
                "id": 27780336,
                "name": "あい",
                "account": "user_guyg7882",
                "profile_image_urls": {
                    "medium": "https://s.pximg.net/common/images/no_profile.png"
                }
            },
            "has_replies": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": null
```

## https://app-api.pixiv.net/v1/novel/comment/replies

Retrieves a list of replies to the specified comment of a novel.

**Requires authorisation header**

**GET request**

### Parameters

commend_id - e.g. `123456`

### Example Response

**Headers**

comment_id - `23848124`

**Response**

```json
{
    "comments": [
        {
            "id": 23848566,
            "comment": "(╭☞•́⍛•̀)╭☞それな\n兄上は神様。\n異論は認めない。",
            "date": "2019-12-10T17:05:00+09:00",
            "user": {
                "id": 14433930,
                "name": "フラミンゴ",
                "account": "rinrinpct",
                "profile_image_urls": {
                    "medium": "https://s.pximg.net/common/images/no_profile.png"
                }
            },
            "has_replies": false
        }
    ],
    "next_url": null
}
```

## https://app-api.pixiv.net/v2/novel/bookmark/add

Adds the specified novel to the user's bookmarks.

**Requires authorisation header**

**POST request**

### Parameters

novel_id - `[novel id]`<br>
restrict - `public` `private`

### Example Response

```json
{}
```

## https://app-api.pixiv.net/v1/novel/bookmark/delete

Removes the specified novel from the user's bookmarks.

**Requires authorisation header**

**POST request**

### Parameters

novel_id - `[novel id]`

### Example Response

```json
{}
```
