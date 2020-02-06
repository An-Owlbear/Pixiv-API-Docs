# Browsing Works

## https://app-api.pixiv.net/v1/illust/recommended

Retrieves a list of recommended illustrations.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`
include_ranking_illusts - `true` `false`
include_privacy_policy - `true` `false`

### Example Response

**Pararmeters**

filter - `for_android`
include_ranking_illusts - `true`
include_privacy_policy - `true`

**Response**

```json
{
    "illusts": [
        {
            "id": 76159879,
            "title": "縁×黄",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/08/09/10/00/44/76159879_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/08/09/10/00/44/76159879_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/08/09/10/00/44/76159879_p0_master1200.jpg"
            },
            "caption": "",
            "restrict": 0,
            "user": {
                "id": 1113943,
                "name": "ももこ@3日目南ナ-42a",
                "account": "momopoco",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2015/04/01/09/24/51/9172583_ef46e4bda34c271df88dd5f64c2fba5e_170.png"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "オリジナル",
                    "translated_name": "original"
                },
                {
                    "name": "緑髪",
                    "translated_name": "green hair"
                },
                {
                    "name": "レモン",
                    "translated_name": "lemon"
                },
                {
                    "name": "ライム",
                    "translated_name": "lime"
                },
                {
                    "name": "ナース",
                    "translated_name": "nurse"
                },
                {
                    "name": "ツインテール",
                    "translated_name": "twin ponytails"
                },
                {
                    "name": "聴診器",
                    "translated_name": "stethoscope"
                },
                {
                    "name": "プランジングネック",
                    "translated_name": "plunging neckline"
                },
                {
                    "name": "オリジナル30000users入り",
                    "translated_name": "original 30000+ Bookmarks"
                },
                {
                    "name": "エロ衣装",
                    "translated_name": "sexy clothes"
                }
            ],
            "tools": [],
            "create_date": "2019-08-09T10:00:44+09:00",
            "page_count": 1,
            "width": 1000,
            "height": 1412,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {
                "original_image_url": "https://i.pximg.net/img-original/img/2019/08/09/10/00/44/76159879_p0.jpg"
            },
            "meta_pages": [],
            "total_view": 196813,
            "total_bookmarks": 34194,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "ranking_illusts": [
        {
            "id": 79203687,
            "title": "♡",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/02/01/00/00/10/79203687_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/01/00/00/10/79203687_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/01/00/00/10/79203687_p0_master1200.jpg"
            },
            "caption": "バレンタインっぽい子<br /><br />『Mika Pikazo展2020 全国ツアー』、始まりました！✨<br />最初は仙台のPARCOさんから！<br />1月31日（金）～2月9日（日）開催です、ぜひ！<br />場所：仙台PARCO２ ５F特設   開催日：1月31日（金）～2月9日（日）10:00-21:00<br />詳細: <a href=\"https://www.mikapikazo.com/information/archive/?514749\" target=\"_blank\">https://www.mikapikazo.com/information/archive/?514749</a>",
            "restrict": 0,
            "user": {
                "id": 1039353,
                "name": "Mika Pikazo",
                "account": "igix",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2019/06/08/18/15/46/15864250_3a16ed5563079c651f041ee27950de74_170.png"
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
                    "name": "ピンクバレンタイン",
                    "translated_name": null
                },
                {
                    "name": "ボブカット",
                    "translated_name": "boy-cut"
                },
                {
                    "name": "バレンタインデー",
                    "translated_name": "Valentine's day"
                },
                {
                    "name": "オリジナル10000users入り",
                    "translated_name": "original 10000+ bookmarks"
                }
            ],
            "tools": [],
            "create_date": "2020-02-01T00:00:10+09:00",
            "page_count": 1,
            "width": 965,
            "height": 1300,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {
                "original_image_url": "https://i.pximg.net/img-original/img/2020/02/01/00/00/10/79203687_p0.png"
            },
            "meta_pages": [],
            "total_view": 82061,
            "total_bookmarks": 18786,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "contest_exists": false,
    "privacy_policy": {
        "version": "1-en",
        "message": "pixiv has updated its Privacy Policy to comply with the new EU data protection regulation.",
        "url": "https://www.pixiv.net/terms/?page=privacy&appname=pixiv_ios"
    },
    "next_url": "https://app-api.pixiv.net/v1/illust/recommended?filter=for_android&include_ranking_illusts=false&include_privacy_policy=false&min_bookmark_id_for_recent_illust=7419686721&max_bookmark_id_for_recommend=7419686721&offset=0"
}
```

## https://app-api.pixiv.net/v1/manga/recommended

Retrieves a list of recommended manga.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`
include_ranking_illusts - `true` `false`
include_privacy_policy - `true` `false`

### Example Response

**Parameters**

filter - `for_android`
include_ranking_illusts - `true`
include_privacy_policy - `true`

**Response**

```json
{
    "illusts": [
        {
            "id": 73498778,
            "title": "【PFLS】チチチーチュの大破と脱出",
            "type": "manga",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/03/03/23/33/14/73498778_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/03/03/23/33/14/73498778_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/03/03/23/33/14/73498778_p0_master1200.jpg"
            },
            "caption": "ーこちらの漫画のはがねずみ語の翻訳はできませんでしたー<br /><br />この辺拾わせて頂きました！ふんわりと！<br /><strong><a href=\"pixiv://illusts/73469075\">illust/73469075</a></strong><br /><strong><a href=\"pixiv://illusts/73480949\">illust/73480949</a></strong><br />ギーヴリャさんとは直で戦ったわけではないけど視線に入った的な！<br /><br />破損したチチチーチュは三章までに回収して直します！ありがとうございました！<br /><br />チャチィはパラシュートでふわふわしてますがこのままプチッとトドメさしても助けてもオッケーです！一応PCの為、持ち帰って私物化ペット化だけは勘弁でお願いします！<br />生還したらやったー生き残ってよかったー！！！と中の人は思います。<br />死んじゃったらあーそっかー死んじゃったかー辛いけど仕方ないかなって中の人は思います。<br /><br />キャスト<br />信者ナムチ【<strong><a href=\"pixiv://illusts/72968279\">illust/72968279</a></strong>】<br />豪雪のギーヴリャ【<strong><a href=\"pixiv://illusts/73296807\">illust/73296807</a></strong>】<br />チャチィ【<strong><a href=\"pixiv://illusts/72937855\">illust/72937855</a></strong>】",
            "restrict": 0,
            "user": {
                "id": 246839,
                "name": "サイコツーアウト",
                "account": "saiko0430",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2020/01/30/08/55/18/17827543_d58910f9676d77db66a07fa14da6e7e0_170.jpg"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "漫画",
                    "translated_name": "manga"
                },
                {
                    "name": "pixivファンタジアLS",
                    "translated_name": "pixiv Fantasia: Last Saga"
                },
                {
                    "name": "エルダーグラン",
                    "translated_name": "Eldergran"
                },
                {
                    "name": "灰色熊の戦い【緑】",
                    "translated_name": "The Battle of Grizzly Bear【green】"
                },
                {
                    "name": "【黒梯騎士団ベアステイル】",
                    "translated_name": null
                },
                {
                    "name": "強襲教団エインゲイル",
                    "translated_name": null
                },
                {
                    "name": "【剣聖の息子達】",
                    "translated_name": null
                }
            ],
            "tools": [
                "CLIP STUDIO PAINT"
            ],
            "create_date": "2019-03-03T23:33:14+09:00",
            "page_count": 2,
            "width": 600,
            "height": 800,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {},
            "meta_pages": [
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/03/03/23/33/14/73498778_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/03/03/23/33/14/73498778_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/03/03/23/33/14/73498778_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/03/03/23/33/14/73498778_p0.png"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/03/03/23/33/14/73498778_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/03/03/23/33/14/73498778_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/03/03/23/33/14/73498778_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2019/03/03/23/33/14/73498778_p1.png"
                    }
                }
            ],
            "total_view": 2891,
            "total_bookmarks": 78,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "ranking_illusts": [
        {
            "id": 79299672,
            "title": "【創作】空気が「読める」新入社員と不愛想な先輩の話７",
            "type": "manga",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/02/05/19/00/04/79299672_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/19/00/04/79299672_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/19/00/04/79299672_p0_master1200.jpg"
            },
            "caption": "本編最新話(その8)→<a href=\"https://twitter.com/t_rsa/status/1224618687056896000\" target=\"_blank\">https://twitter.com/t_rsa/status/1224618687056896000</a><br /><br />2/9 COMITIA131　す02bD.Finchでまとめ同人誌頒布予定です。<br />通販⇒<br />フロマージュ<a href=\"https://bit.ly/3aBls7Z\" target=\"_blank\">https://bit.ly/3aBls7Z</a><br />メロンブックス<a href=\"https://bit.ly/30NhB3g\" target=\"_blank\">https://bit.ly/30NhB3g</a><br />アニメイト<a href=\"https://bit.ly/2RkkXYo\" target=\"_blank\">https://bit.ly/2RkkXYo</a>",
            "restrict": 0,
            "user": {
                "id": 164460,
                "name": "鳥原習",
                "account": "toritou",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2016/05/15/12/34/26/10935158_1fc67939022e619ccf12f1230e45002d_170.png"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "漫画",
                    "translated_name": "manga"
                },
                {
                    "name": "オリジナル",
                    "translated_name": "original"
                },
                {
                    "name": "創作男女",
                    "translated_name": "original male and female characters"
                },
                {
                    "name": "スーツ",
                    "translated_name": "suit"
                },
                {
                    "name": "なにこれほっこり",
                    "translated_name": null
                },
                {
                    "name": "甘い(2つの意味で)",
                    "translated_name": null
                },
                {
                    "name": "何て素敵",
                    "translated_name": null
                }
            ],
            "tools": [],
            "create_date": "2020-02-05T19:00:04+09:00",
            "page_count": 6,
            "width": 800,
            "height": 1127,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": {
                "id": 55572,
                "title": "空気が「読める」新入社員と不愛想な先輩の話"
            },
            "meta_single_page": {},
            "meta_pages": [
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/02/05/19/00/04/79299672_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/19/00/04/79299672_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/19/00/04/79299672_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/02/05/19/00/04/79299672_p0.png"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/02/05/19/00/04/79299672_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/19/00/04/79299672_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/19/00/04/79299672_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/02/05/19/00/04/79299672_p1.png"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/02/05/19/00/04/79299672_p2_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/19/00/04/79299672_p2_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/19/00/04/79299672_p2_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/02/05/19/00/04/79299672_p2.png"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/02/05/19/00/04/79299672_p3_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/19/00/04/79299672_p3_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/19/00/04/79299672_p3_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/02/05/19/00/04/79299672_p3.png"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/02/05/19/00/04/79299672_p4_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/19/00/04/79299672_p4_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/19/00/04/79299672_p4_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/02/05/19/00/04/79299672_p4.png"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/02/05/19/00/04/79299672_p5_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/19/00/04/79299672_p5_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/19/00/04/79299672_p5_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/02/05/19/00/04/79299672_p5.png"
                    }
                }
            ],
            "total_view": 67166,
            "total_bookmarks": 6991,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "privacy_policy": {
        "version": "1-en",
        "message": "pixiv has updated its Privacy Policy to comply with the new EU data protection regulation.",
        "url": "https://www.pixiv.net/terms/?page=privacy&appname=pixiv_ios"
    },
    "next_url": "https://app-api.pixiv.net/v1/manga/recommended?filter=for_android&include_ranking_illusts=false&include_privacy_policy=false&max_bookmark_id=7419686721&offset=30"
}
```

## https://app-api.pixiv.net/v1/novel/recommended

Retrieves a list of recommended novels.

**Requires authorisation header**

**GET request**

### Parameters

include_ranking_novels - `true` `false`
include_privacy_policy - `true` `false`

### Example Response

**Parameters**

include_ranking_novels - `true`
include_privacy_policy - `true

**Response**

```json
{
    "novels": [
        {
            "id": 11363846,
            "title": "鉄人乙女は言葉選びが下手",
            "caption": "鬼滅の刃世界でも毛探偵に出てくる鉄人なら余裕で生き残れるなと思った結果です。シリーズのつもり。<br /><br />閲覧は自己責任で。苦情は一切受け付けません。",
            "restrict": 0,
            "x_restrict": 0,
            "is_original": false,
            "image_urls": {
                "square_medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_128x128.jpg",
                "medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_176mw.jpg",
                "large": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_240mw.jpg"
            },
            "create_date": "2019-07-06T23:44:38+09:00",
            "tags": [
                {
                    "name": "鬼滅の夢",
                    "translated_name": "Kimetsu no Yaiba original",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "オリ主",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "転生",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "続きを正座待機",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "クロスオーバー",
                    "translated_name": "crossover",
                    "added_by_uploaded_user": false
                },
                {
                    "name": "鬼滅の夢小説3000users入り",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "混合夢小説3000users入り",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                }
            ],
            "page_count": 5,
            "text_length": 14561,
            "user": {
                "id": 7286081,
                "name": "狐＠なろうに浮気中",
                "account": "801801965",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2017/07/06/21/08/54/12815611_d3b1e7b475081a074ecf13be00b30f30_170.jpg"
                },
                "is_followed": false
            },
            "series": {
                "id": 1145068,
                "title": "鉄人…ではなく鉄柱、参ります"
            },
            "is_bookmarked": false,
            "total_bookmarks": 3756,
            "total_view": 35964,
            "visible": true,
            "total_comments": 46,
            "is_muted": false,
            "is_mypixiv_only": false,
            "is_x_restricted": false
        },
        {
            "etc": "etc"
        }
    ],
    "ranking_novels": [
        {
            "id": 12323235,
            "title": "彼氏にほとほと愛想を尽かしたので私はガラルに逃亡します　12",
            "caption": "前作【<strong><a href=\"pixiv://novels/12308179\">novel/12308179</a></strong>】<br /><br />オリ主「此処まで夢主の出番がない話ある？？？？？」<br /><br />マジカル交換でいじっぱり5Vミミッキュくれた人マジで誰！！！？？？？サンキュー！！！！！！！！！<br />ドラパルトちゃんとバンギラスくんがレベル100になったで！やったね！<br />夢特性アーマーガア？知らない子ですね…<br />最近剣盾二週目してるんですけどもうダンデホップ兄弟愛おしすぎてスクショ止まらんしオリーヴさん好きすぎて　あの　あなたのリーグカードが欲しいんです私ィ！！！！！剣盾楽しい！！ガラル箱推しです！！！好き！！！永住したい！！！！！！！！！バトルタワーに就職させてください<br /><br />追記：サーナイトの特性はフェアリースキンやないでというお話をいくつか頂いたんですけれども、サーナイトの特性はシンクロでもトレースでもメガシンカするとフェアリースキンに変更されるので、『ハイパーボイス』はフェアリースキンの特性を最大限活用できるように組み込まれたメガシンカ用編成技です。ちなみに普段の特性はシンクロの設定です。一応メッセージでもそのように返信はしたのだけれど、一応こちらでも。……合ってるよね？不安になって来た",
            "restrict": 0,
            "x_restrict": 0,
            "is_original": false,
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/128x128/novel-cover-master/img/2020/02/04/15/43/13/12323235_f6a168e4f72bf7f9a378e930918bbb24_square1200.jpg",
                "medium": "https://i.pximg.net/c/176x352/novel-cover-master/img/2020/02/04/15/43/13/12323235_f6a168e4f72bf7f9a378e930918bbb24_master1200.jpg",
                "large": "https://i.pximg.net/c/240x480_80/novel-cover-master/img/2020/02/04/15/43/13/12323235_f6a168e4f72bf7f9a378e930918bbb24_master1200.jpg"
            },
            "create_date": "2020-02-04T15:43:13+09:00",
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
                    "name": "転生",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "ダンデ",
                    "translated_name": "Leon",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "ネモネ守り隊がアップを始めました",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "さて…元彼殺るか",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "さぁ獲物(元彼)をハンティング(仕留め)に皆行こうか。",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "とうとうこの日が来たんですね!!!!!",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "積みに積んだバフで元彼を殴れ",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                },
                {
                    "name": "お前の死が来たぞ!",
                    "translated_name": null,
                    "added_by_uploaded_user": false
                }
            ],
            "page_count": 5,
            "text_length": 11471,
            "user": {
                "id": 46805038,
                "name": "麦ソーダ",
                "account": "user_thsn7572",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2020/01/07/17/08/38/16815774_c3659d9ca1dfbe9f9438fb6d6985bc39_170.jpg"
                },
                "is_followed": false
            },
            "series": {
                "id": 1233069,
                "title": "こんな所にいられるか！私はガラルに逃げるぞ！"
            },
            "is_bookmarked": false,
            "total_bookmarks": 3103,
            "total_view": 20425,
            "visible": true,
            "total_comments": 110,
            "is_muted": false,
            "is_mypixiv_only": false,
            "is_x_restricted": false
        },
        {
            "etc": "etc"
        }
    ],
    "privacy_policy": {
        "version": "1-en",
        "message": "pixiv has updated its Privacy Policy to comply with the new EU data protection regulation.",
        "url": "https://www.pixiv.net/terms/?page=privacy&appname=pixiv_ios"
    },
    "next_url": "https://app-api.pixiv.net/v1/novel/recommended?include_ranking_novels=false&include_privacy_policy=false&offset=15&max_bookmark_id_for_recommend=0"
}
```

## https://app-api.pixiv.net/v1/user/recommended

Retrieves a list of recommended users

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`

### Example Response

**Parameters**

filter - `for_android`

**Response**

```json
{
    "user_previews": [
        {
            "user": {
                "id": 444732,
                "name": "れい亜",
                "account": "marin_marin",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2019/06/12/17/31/26/15881113_37752dde725b2b7069688656d7bf3fd2_170.jpg"
                },
                "is_followed": false
            },
            "illusts": [
                {
                    "id": 79288135,
                    "title": "デザイア・オーダー",
                    "type": "illust",
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/02/05/00/00/10/79288135_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/00/00/10/79288135_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/00/00/10/79288135_p0_master1200.jpg"
                    },
                    "caption": "本日２月５日にLINE文庫エッジ様より刊行の波摘先生著作『デザイア・オーダー　―生存率1％の戦場―』の挿絵を担当させていただきました！！圧倒的戦闘力を持った未知の敵とのギリギリのバトルをぜひ楽しんでいただけたら嬉しいです！！<br /><a href=\"https://amazon.co.jp/dp/4910040358/ref=cm_sw_r_tw_dp_U_x_etQnEbMPXY274\" target=\"_blank\">https://amazon.co.jp/dp/4910040358/ref=cm_sw_r_tw_dp_U_x_etQnEbMPXY274</a>",
                    "restrict": 0,
                    "user": {
                        "id": 444732,
                        "name": "れい亜",
                        "account": "marin_marin",
                        "profile_image_urls": {
                            "medium": "https://i.pximg.net/user-profile/img/2019/06/12/17/31/26/15881113_37752dde725b2b7069688656d7bf3fd2_170.jpg"
                        },
                        "is_followed": false
                    },
                    "tags": [
                        {
                            "name": "ライトノベル",
                            "translated_name": "light novel"
                        },
                        {
                            "name": "デザイア・オーダー",
                            "translated_name": null
                        }
                    ],
                    "tools": [],
                    "create_date": "2020-02-05T00:00:10+09:00",
                    "page_count": 1,
                    "width": 623,
                    "height": 900,
                    "sanity_level": 2,
                    "x_restrict": 0,
                    "series": null,
                    "meta_single_page": {
                        "original_image_url": "https://i.pximg.net/img-original/img/2020/02/05/00/00/10/79288135_p0.png"
                    },
                    "meta_pages": [],
                    "total_view": 10079,
                    "total_bookmarks": 1505,
                    "is_bookmarked": false,
                    "visible": true,
                    "is_muted": false
                },
                {
                    "id": 76224857,
                    "title": "新刊「強キャラ系女子」",
                    "type": "illust",
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/08/13/00/00/08/76224857_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/08/13/00/00/08/76224857_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/08/13/00/00/08/76224857_p0_master1200.jpg"
                    },
                    "caption": "コミケで頒布した新刊「強キャラ系女子」の委託予約始まっております〜〜！！気になった方はこちらからもどうぞよろしくお願いいたします！😊<br /><br />とらのあな🐯：<a href=\"https://ec.toranoana.shop/tora/ec/item/040030765871\" target=\"_blank\">https://ec.toranoana.shop/tora/ec/item/040030765871</a><br />メロンブックス🍈：<a href=\"https://www.melonbooks.co.jp/detail/detail.php?product_id=546938\" target=\"_blank\">https://www.melonbooks.co.jp/detail/detail.php?product_id=546938</a><br /><br />夏コミお疲れ様でした！！<br />たくさんの方にきていただきお手にとっていただけて本当に胸いっぱいです…！<br />ありがとうございました！",
                    "restrict": 0,
                    "user": {
                        "id": 444732,
                        "name": "れい亜",
                        "account": "marin_marin",
                        "profile_image_urls": {
                            "medium": "https://i.pximg.net/user-profile/img/2019/06/12/17/31/26/15881113_37752dde725b2b7069688656d7bf3fd2_170.jpg"
                        },
                        "is_followed": false
                    },
                    "tags": [
                        {
                            "name": "オリジナル",
                            "translated_name": "original"
                        },
                        {
                            "name": "強キャラ系女子",
                            "translated_name": null
                        },
                        {
                            "name": "刀",
                            "translated_name": "katana"
                        },
                        {
                            "name": "抜刀",
                            "translated_name": null
                        },
                        {
                            "name": "セーラー服",
                            "translated_name": "sailor uniform"
                        },
                        {
                            "name": "セーラー服と日本刀",
                            "translated_name": null
                        },
                        {
                            "name": "オリジナル10000users入り",
                            "translated_name": "original 10000+ bookmarks"
                        },
                        {
                            "name": "帯刀女子高生",
                            "translated_name": "sword-carrying high school girl"
                        },
                        {
                            "name": "勝てる気がしない",
                            "translated_name": "feels like we can't win"
                        }
                    ],
                    "tools": [],
                    "create_date": "2019-08-13T00:00:08+09:00",
                    "page_count": 1,
                    "width": 639,
                    "height": 900,
                    "sanity_level": 2,
                    "x_restrict": 0,
                    "series": null,
                    "meta_single_page": {
                        "original_image_url": "https://i.pximg.net/img-original/img/2019/08/13/00/00/08/76224857_p0.png"
                    },
                    "meta_pages": [],
                    "total_view": 138793,
                    "total_bookmarks": 26146,
                    "is_bookmarked": false,
                    "visible": true,
                    "is_muted": false
                },
                {
                    "id": 76163154,
                    "title": "ありゃ〜",
                    "type": "illust",
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/08/09/15/40/29/76163154_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/08/09/15/40/29/76163154_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/08/09/15/40/29/76163154_p0_master1200.jpg"
                    },
                    "caption": "C96にて頒布するグッズセットのクリアファイルに使用したイラストです！普通のクリアファイルより厚みのあるしっかりした素材を使用しております〜！<br />夏コミ当日はどうぞよろしくお願いいたします！😊<br /><br />新刊「強キャラ系女子」の通販も始まってますのでぜひ〜！<br /><br />とらのあな🐯　<a href=\"https://ec.toranoana.shop/tora/ec/item/040030765871\" target=\"_blank\">https://ec.toranoana.shop/tora/ec/item/040030765871</a><br />メロンブックス🍈　<a href=\"https://www.melonbooks.co.jp/detail/detail.php?product_id=546938\" target=\"_blank\">https://www.melonbooks.co.jp/detail/detail.php?product_id=546938</a>",
                    "restrict": 0,
                    "user": {
                        "id": 444732,
                        "name": "れい亜",
                        "account": "marin_marin",
                        "profile_image_urls": {
                            "medium": "https://i.pximg.net/user-profile/img/2019/06/12/17/31/26/15881113_37752dde725b2b7069688656d7bf3fd2_170.jpg"
                        },
                        "is_followed": false
                    },
                    "tags": [
                        {
                            "name": "オリジナル",
                            "translated_name": "original"
                        },
                        {
                            "name": "強キャラ系女子",
                            "translated_name": null
                        },
                        {
                            "name": "女の子",
                            "translated_name": "girl"
                        },
                        {
                            "name": "ハイカットスニーカー",
                            "translated_name": "high cut sneaker"
                        },
                        {
                            "name": "サイハイソックス",
                            "translated_name": "thigh-highs"
                        },
                        {
                            "name": "セーラー服",
                            "translated_name": "sailor uniform"
                        },
                        {
                            "name": "コンバース",
                            "translated_name": "Sussex"
                        },
                        {
                            "name": "オリジナル7500users入り",
                            "translated_name": "original 7,500+ bookmarks"
                        }
                    ],
                    "tools": [],
                    "create_date": "2019-08-09T15:40:29+09:00",
                    "page_count": 1,
                    "width": 637,
                    "height": 900,
                    "sanity_level": 2,
                    "x_restrict": 0,
                    "series": null,
                    "meta_single_page": {
                        "original_image_url": "https://i.pximg.net/img-original/img/2019/08/09/15/40/29/76163154_p0.png"
                    },
                    "meta_pages": [],
                    "total_view": 50631,
                    "total_bookmarks": 8160,
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
    "next_url": "https://app-api.pixiv.net/v1/user/recommended?filter=for_android&offset=30"
}
```

## https://app-api.pixiv.net/v1/illust/new

Retrieves a list of newly uploaded illustrations/manga.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`
content_type - `illust` `manga`

### Example Response

**Parameters**

filter - `for_android`
content_type - `illust`

```json
{
    "illusts": [
        {
            "id": 79322043,
            "title": "フェンちゃん",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/02/06/22/39/41/79322043_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/06/22/39/41/79322043_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/06/22/39/41/79322043_p0_master1200.jpg"
            },
            "caption": "これはフェンちゃんが冬スキンをきている時にロドスに復帰して対応をまちがえたドクター",
            "restrict": 0,
            "user": {
                "id": 5303964,
                "name": "狐目",
                "account": "ag-ky-ry",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2020/01/22/00/37/35/16887283_ddab602546d14d2873961bc750fd9e84_170.jpg"
                },
                "is_followed": false
            },
            "tags": [
                {
                    "name": "明日方舟",
                    "translated_name": "Arknights"
                },
                {
                    "name": "アークナイツ",
                    "translated_name": "Arknights"
                },
                {
                    "name": "Arknights",
                    "translated_name": null
                },
                {
                    "name": "フェン(アークナイツ)",
                    "translated_name": null
                }
            ],
            "tools": [],
            "create_date": "2020-02-06T22:39:41+09:00",
            "page_count": 1,
            "width": 2039,
            "height": 2894,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {
                "original_image_url": "https://i.pximg.net/img-original/img/2020/02/06/22/39/41/79322043_p0.jpg"
            },
            "meta_pages": [],
            "total_view": 7,
            "total_bookmarks": 0,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": "https://app-api.pixiv.net/v1/illust/new?filter=for_android&content_type=illust&max_illust_id=79321934"
}
```

## https://app-api.pixiv.net/v2/illust/follow

Retrieves a list of newly uploaded illustrations/manga from followed users.

**Requires authorisation header**

**GET request**

### Parameters

restrict - `all` `public` `private`

### Example Response

**Parameters**

restrict - `all`

**Response**

```json
{
    "illusts": [
        {
            "id": 79296148,
            "title": "pixivオリジナル企画「百合イラストコンテスト2」開催",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/02/05/14/11/43/79296148_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/14/11/43/79296148_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/14/11/43/79296148_p0_master1200.jpg"
            },
            "caption": "pixiv事務局です。<br /><br />5月8日（水）よりpixivオリジナル企画「百合イラストコンテスト2」を開催します。<br />本コンテストでは、GWに開催されるイベント「コミックマーケット98」pixivブースにて販売する画集「pixiv百合画集（仮）」へ掲載するイラストを募集します。<br /><br />百合を愛するすべての人が、それぞれの百合を表現する機会・場所を作りたい。そして百合の魅力をより多くのみなさんへと伝えたい。そんな想いから、本コンテストの開催および画集の製造・販売を決定しました。<br /><br />pixivおよびコミックマーケットは、どちらも自分が好きな創作活動を発信できる場です。数多くの同好の士が集まるリアルイベントで、pixiv公式画集というかたちで、ご自身の作品を発信してみませんか。<br /><br />みなさまからのご応募、お待ちしております。<br /><br />＜これまでのpixivコミックマーケット出展情報はこちら＞<br /><a href=\"https://goods.pixiv.net/\" target=\"_blank\">https://goods.pixiv.net/</a><br /><br /><strong>【開催期間】</strong><br />2020年2月5日（水）〜3月5日（木）23:59<br /><br /><strong>【参加方法】</strong><br />女性同士の恋愛や友愛をテーマに、オリジナルの百合イラストをお描きください。「両想いなのに素直になれない二人」「年の差カップル」など、理想とするさまざまな設定・シチュエーションをイラストに描き起こしましょう。年齢や性格などの規定は一切ありません。あなたの愛する百合をご自由にお描きください。<br /><br />pixivにおいて、以下に定めるタグを設定して作品(イラスト)を投稿してください。<br />タグ：<span style=\"color:#ff0000;\">百合イラコン2</span><br /><br />（任意で）キャプションに設定やシチュエーションをお書きください。百合ドラマ賞を受賞した場合のボイスドラマ制作の参考とさせていただきます。<br /><br /><strong>【投稿形式】</strong><br />投稿数：1点以上複数作品の投稿可能（ただし、同じ作品を複数投稿することはできません）。<br />Web投稿画像サイズ：投稿時のサイズは自由です。<br />ただし、受賞者の方は「縦横問わずB5サイズ（2508pixel×3541pixel）以上、解像度350dpi、psdデータ、CMYK」で作品のデータのご提出をお願いします。<br /><br /><strong>【選考方法】</strong><br />厳正なる審査の後、優秀作品を決定します。<br /><br /><strong>【受賞賞品】</strong><br />百合ドラマ賞（1名）<br />・作品をイメージした百合ボイスドラマ（プロ声優を起用）を制作し、「pixiv百合画集（仮）」特典に使用<br />・pixivオリジナル電子マネーカード(2&#44;000円分)を進呈<br />・pixivが発行する画集「pixiv百合画集（仮）」への掲載・進呈<br /><br />pixiv賞（複数名）<br />・pixivオリジナル電子マネーカード(2&#44;000円分)を進呈<br />・pixivが発行する画集「pixiv百合画集（仮）」への掲載・進呈<br /><br />※「pixiv百合画集（仮）」はGWに開催されるイベント「コミックマーケット98」pixivブースにて販売予定の画集です。<br /><br />◆応募作品一覧ページ <a href=\"https://www.pixiv.net/contest/yuri2\" target=\"_blank\">https://www.pixiv.net/contest/yuri2</a>",
            "restrict": 0,
            "user": {
                "id": 11,
                "name": "pixiv事務局",
                "account": "pixiv",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2018/04/26/17/49/29/14143210_7f79090d53f5b1befad3ba07818d89dd_170.jpg"
                },
                "is_followed": true
            },
            "tags": [
                {
                    "name": "公式企画",
                    "translated_name": null
                },
                {
                    "name": "企画目録",
                    "translated_name": null
                },
                {
                    "name": "百合イラコン2",
                    "translated_name": null
                },
                {
                    "name": "C98",
                    "translated_name": null
                },
                {
                    "name": "百合",
                    "translated_name": "yuri"
                },
                {
                    "name": "オリジナル",
                    "translated_name": "original"
                }
            ],
            "tools": [],
            "create_date": "2020-02-05T14:11:43+09:00",
            "page_count": 1,
            "width": 960,
            "height": 964,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {
                "original_image_url": "https://i.pximg.net/img-original/img/2020/02/05/14/11/43/79296148_p0.png"
            },
            "meta_pages": [],
            "total_view": 59132,
            "total_bookmarks": 2343,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": "https://app-api.pixiv.net/v2/illust/follow?restrict=public&offset=30"
}
```

## https://app-api.pixiv.net/v2/illust/mypixiv

Retrieves a list of new illustrations/manga from users added to my pixiv.

**Requires authorisation header**

**GET Request**

## https://app-api.pixiv.net/v1/novel/new

Retrieves a list of new novels.

**Requires authorisation header**

**GET request**

### Example Response

```json
{
    "novels": [
        {
            "id": 12333650,
            "title": "「140字で太芥」まとめ【1月分】2周目",
            "caption": "Twitterで連載している140字SS「140字で太芥」（正確には134字以内、ときどき大幅オーバー）の、1月分2周目のまとめです。<br />表記揺れは統一していませんが、一部ふりがなを振ったり、検索除けのために単語の間に入れたアルファベットを消したりはしています。",
            "restrict": 0,
            "x_restrict": 0,
            "is_original": false,
            "image_urls": {
                "square_medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_128x128.jpg",
                "medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_176mw.jpg",
                "large": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_240mw.jpg"
            },
            "create_date": "2020-02-06T22:51:16+09:00",
            "tags": [
                {
                    "name": "文豪ストレイドッグス",
                    "translated_name": "Bungo Stray Dogs",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "文スト【腐】",
                    "translated_name": "Bungo Stray Dogs BL fanwork",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "太芥",
                    "translated_name": "Dazai/Ryunosuke",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "太宰治(文豪ストレイドッグス)",
                    "translated_name": "Osamu Dazai (Bungo Stray Dogs)",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "芥川龍之介(文豪ストレイドッグス)",
                    "translated_name": "Ryūnosuke Akutagawa",
                    "added_by_uploaded_user": true
                }
            ],
            "page_count": 1,
            "text_length": 3722,
            "user": {
                "id": 23247430,
                "name": "えん@BOOTH通販中",
                "account": "user_tjyj5243",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2017/05/21/20/11/40/12589188_afaf168b4659e05e20fa1975e7a33475_170.jpg"
                },
                "is_followed": false
            },
            "series": {
                "id": 985696,
                "title": "140字で太芥"
            },
            "is_bookmarked": false,
            "total_bookmarks": 0,
            "total_view": 0,
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
    "next_url": "https://app-api.pixiv.net/v1/novel/new?max_novel_id=12333608"
}
```

### https://app-api.pixiv.net/v2/illust/follow

Retrieves a list of new illustrations/manga from followed users.

**Requires authorisation header**

**GET request**

### Parameters

restrict - `all` `public` `private`

### Example Response

**Parameters**

restrict - `all`

**Response**

```json
{
    "illusts": [
        {
            "id": 79296148,
            "title": "pixivオリジナル企画「百合イラストコンテスト2」開催",
            "type": "illust",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/02/05/14/11/43/79296148_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/05/14/11/43/79296148_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/05/14/11/43/79296148_p0_master1200.jpg"
            },
            "caption": "pixiv事務局です。<br /><br />5月8日（水）よりpixivオリジナル企画「百合イラストコンテスト2」を開催します。<br />本コンテストでは、GWに開催されるイベント「コミックマーケット98」pixivブースにて販売する画集「pixiv百合画集（仮）」へ掲載するイラストを募集します。<br /><br />百合を愛するすべての人が、それぞれの百合を表現する機会・場所を作りたい。そして百合の魅力をより多くのみなさんへと伝えたい。そんな想いから、本コンテストの開催および画集の製造・販売を決定しました。<br /><br />pixivおよびコミックマーケットは、どちらも自分が好きな創作活動を発信できる場です。数多くの同好の士が集まるリアルイベントで、pixiv公式画集というかたちで、ご自身の作品を発信してみませんか。<br /><br />みなさまからのご応募、お待ちしております。<br /><br />＜これまでのpixivコミックマーケット出展情報はこちら＞<br /><a href=\"https://goods.pixiv.net/\" target=\"_blank\">https://goods.pixiv.net/</a><br /><br /><strong>【開催期間】</strong><br />2020年2月5日（水）〜3月5日（木）23:59<br /><br /><strong>【参加方法】</strong><br />女性同士の恋愛や友愛をテーマに、オリジナルの百合イラストをお描きください。「両想いなのに素直になれない二人」「年の差カップル」など、理想とするさまざまな設定・シチュエーションをイラストに描き起こしましょう。年齢や性格などの規定は一切ありません。あなたの愛する百合をご自由にお描きください。<br /><br />pixivにおいて、以下に定めるタグを設定して作品(イラスト)を投稿してください。<br />タグ：<span style=\"color:#ff0000;\">百合イラコン2</span><br /><br />（任意で）キャプションに設定やシチュエーションをお書きください。百合ドラマ賞を受賞した場合のボイスドラマ制作の参考とさせていただきます。<br /><br /><strong>【投稿形式】</strong><br />投稿数：1点以上複数作品の投稿可能（ただし、同じ作品を複数投稿することはできません）。<br />Web投稿画像サイズ：投稿時のサイズは自由です。<br />ただし、受賞者の方は「縦横問わずB5サイズ（2508pixel×3541pixel）以上、解像度350dpi、psdデータ、CMYK」で作品のデータのご提出をお願いします。<br /><br /><strong>【選考方法】</strong><br />厳正なる審査の後、優秀作品を決定します。<br /><br /><strong>【受賞賞品】</strong><br />百合ドラマ賞（1名）<br />・作品をイメージした百合ボイスドラマ（プロ声優を起用）を制作し、「pixiv百合画集（仮）」特典に使用<br />・pixivオリジナル電子マネーカード(2&#44;000円分)を進呈<br />・pixivが発行する画集「pixiv百合画集（仮）」への掲載・進呈<br /><br />pixiv賞（複数名）<br />・pixivオリジナル電子マネーカード(2&#44;000円分)を進呈<br />・pixivが発行する画集「pixiv百合画集（仮）」への掲載・進呈<br /><br />※「pixiv百合画集（仮）」はGWに開催されるイベント「コミックマーケット98」pixivブースにて販売予定の画集です。<br /><br />◆応募作品一覧ページ <a href=\"https://www.pixiv.net/contest/yuri2\" target=\"_blank\">https://www.pixiv.net/contest/yuri2</a>",
            "restrict": 0,
            "user": {
                "id": 11,
                "name": "pixiv事務局",
                "account": "pixiv",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2018/04/26/17/49/29/14143210_7f79090d53f5b1befad3ba07818d89dd_170.jpg"
                },
                "is_followed": true
            },
            "tags": [
                {
                    "name": "公式企画",
                    "translated_name": null
                },
                {
                    "name": "企画目録",
                    "translated_name": null
                },
                {
                    "name": "百合イラコン2",
                    "translated_name": null
                },
                {
                    "name": "C98",
                    "translated_name": null
                },
                {
                    "name": "百合",
                    "translated_name": "yuri"
                },
                {
                    "name": "オリジナル",
                    "translated_name": "original"
                }
            ],
            "tools": [],
            "create_date": "2020-02-05T14:11:43+09:00",
            "page_count": 1,
            "width": 960,
            "height": 964,
            "sanity_level": 2,
            "x_restrict": 0,
            "series": null,
            "meta_single_page": {
                "original_image_url": "https://i.pximg.net/img-original/img/2020/02/05/14/11/43/79296148_p0.png"
            },
            "meta_pages": [],
            "total_view": 58974,
            "total_bookmarks": 2337,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": "https://app-api.pixiv.net/v2/illust/follow?restrict=public&offset=30"
}
```

## https://app-api.pixiv.net/v1/novel/follow

Retrieves a list of new novels from followed users.

**Requires authorisation header**

**GET request**

### Parameters

restrict - `all` `public` `private`

### Example Response

**Parameters**

restrict - `public`

**Response**

```json
{
    "novels": [
        {
            "id": 12116635,
            "title": "「pixivノベル大賞～2019Winter～」開催！",
            "caption": "pixiv事務局です。<br /><br />12月23日（月）より「pixivノベル大賞～2019Winter～」を開催します。本コンテストでは、各部門のテーマに沿った小説を募集します。優秀作品には賞金が贈られるほか、表紙イラスト付きでpixivノベルに掲載されます。<br /><br /><strong>「▼pixivノベルとは」</strong><br />たくさんの小説の無料試し読みや連載小説を楽しめるノベルサービスです。<br />新着タイトルも続々公開中！<br /><a href=\"https://novel.pixiv.net/\" target=\"_blank\">https://novel.pixiv.net/</a><br /><br />【応募期間】<span style=\"color:#ff0000;\">2019年12月23日（月）～2020年2月24日（月） 23:59</span><br /><br />【応募要項】<br />各部門のテーマに沿った小説を募集します。<br /><br />【応募部門】<br />・異世界ファンタジー部門<br />・現代ファンタジー部門<br />・SF部門<br />・歴史・時代部門<br /><br />【投稿形式】<br />（１） pixivの小説投稿機能を使用し、オリジナル小説を投稿してください。その際、下記の3点を行ってください。<br />・pixivの小説投稿機能からシリーズを作成してください。<br />　シリーズの「表現内容：オリジナル」にチェックを入れてください。<br />・シリーズに、応募したい部門の【ジャンル】を設定してください。<br />・第1話にあたる作品に、以下に定めるタグを設定してください。<br /><br />異世界ファンタジー部門<br />異世界を舞台としたファンタジー作品を募集します。<br />ジャンル：異世界ファンタジー<br />タグ：<span style=\"color:#ff0000;\">pixivノベル19冬_異世界F</span><br /><br />現代ファンタジー部門<br />現代世界にファンタジー要素を取り入れた作品を募集します。<br />ジャンル：現代ファンタジー<br />タグ：<span style=\"color:#ff0000;\">pixivノベル19冬_現代F</span><br /><br />SF部門<br />科学的な空想にもとづいた作品。サイエンス・フィクションを募集します。<br />ジャンル：SF<br />タグ：<span style=\"color:#ff0000;\">pixivノベル19冬_SF</span><br /><br />歴史・時代部門<br />過去の時代・人物・出来事などを題材とした作品を募集します。<br />ジャンル：歴史・時代<br />タグ：<span style=\"color:#ff0000;\">pixivノベル19冬_歴史時代</span><br /><br />（２）ご応募いただく小説（以下「応募作品」といいます）の文字数の下限は1&#44;200字以上とし、上限はありません。なお、締め切りまでに最終話を投稿してください。未完結作品は選考対象外となります。完結作品であることがわかるよう、完結したタイミングでシリーズのステータスを「完結済」としてください。<br /><br />（３）応募作品の内容は、日本語で記述されたもの、全年齢向けのものに限らせていただきます。<br /><br />（４）応募作品投稿時、シリーズあらすじに50字以上のあらすじを記載してください（あらすじ以外の内容は記載しないでください）。<br /><br />（５） 応募作品が受賞した場合、当該作品の元データ（保存形式は問いません）をご提供いただくことがありますので、データを削除・紛失等しないよう、ご注意ください。<br /><br />（６） お1人様で何シリーズでもご応募いただけますが、1回の投稿につき、1作品（1連載1シリーズ作品）のみとさせていただきます。<br />NG例：シリーズ名を「pixivノベル大賞応募作品集」とし、複数の異なる作品を登録する。<br /><br />（７）応募作品は、未発表・オリジナルのもの・ご自身に著作権があるものに限らせていただきます。本企画の結果発表前に、応募作品が本企画以外のコンテスト等で受賞した場合には、選考対象外となります。ただし、本企画へ応募する前に、応募者自身が主催・運営するブログ等のWebサイト、応募者自身で作品の修正・削除等が可能な非営利目的の小説投稿サイト（pixivを含む）、応募者自身が非営利目的で制作・発行した同人誌で発表された作品、過去に本企画以外のコンテストに投稿し選外となった作品は、未発表作品とみなされます。<br /><br />【参加資格】<br />pixivの利用登録者であって、本応募要項すべてに同意された個人。プロ・アマは問いません。法人および複数の方による共同作品は、選考対象外となります。<br />※18歳未満の方は、本応募要項への保護者の同意を得た上でご投稿ください。<br /><br />【注意事項】<br />※以下に該当する場合は選考の対象外となりますのであらかじめご了承ください。<br />・応募テーマに関連のない作品。<br />・未完結の作品。<br />・1話にコンテスト指定タグが設定されていない作品。<br />・ジャンルが未設定のシリーズ。<br />・公開範囲が「マイピク限定」「非公開」の作品。<br />・投稿期間を過ぎて投稿、編集された作品。<br />・その他、「応募要項の注意事項」に当てはまる作品。<br /><br />【受賞賞品】<br />■pixivノベル賞<br />各部門から1名<br />賞金3万円＋pixivノベルに表紙イラスト付きで掲載<br /><br />■投稿者の中から抽選<br />40名<br />賞品：Amazonギフトコード1&#44;000円分<br /><br />みなさまからのご応募お待ちしております。<br /><br />◆コンテストページ　<a href=\"https://www.pixiv.net/novel/contest/novel19winter\" target=\"_blank\">https://www.pixiv.net/novel/contest/novel19winter</a><br />◆pixivノベル　<a href=\"https://novel.pixiv.net/\" target=\"_blank\">https://novel.pixiv.net/</a><br />◆pixiv小説編集部Twitter　<strong><a href=\"https://twitter.com/pixiv_shosetsu\" target=\"_blank\">twitter/pixiv_shosetsu</a></strong>",
            "restrict": 0,
            "x_restrict": 0,
            "is_original": true,
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/128x128/novel-cover-master/img/2019/12/23/12/19/22/12116635_07021ce8e2746e9c874746abc8a63259_square1200.jpg",
                "medium": "https://i.pximg.net/c/176x352/novel-cover-master/img/2019/12/23/12/19/22/12116635_07021ce8e2746e9c874746abc8a63259_master1200.jpg",
                "large": "https://i.pximg.net/c/240x480_80/novel-cover-master/img/2019/12/23/12/19/22/12116635_07021ce8e2746e9c874746abc8a63259_master1200.jpg"
            },
            "create_date": "2019-12-23T12:19:22+09:00",
            "tags": [
                {
                    "name": "公式企画",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "企画目録",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "pixivノベル19冬_異世界F",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "pixivノベル19冬_現代F",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "pixivノベル19冬_SF",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "pixivノベル19冬_歴史時代",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                }
            ],
            "page_count": 1,
            "text_length": 23,
            "user": {
                "id": 11,
                "name": "pixiv事務局",
                "account": "pixiv",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2018/04/26/17/49/29/14143210_7f79090d53f5b1befad3ba07818d89dd_170.jpg"
                },
                "is_followed": true
            },
            "series": {},
            "is_bookmarked": false,
            "total_bookmarks": 341,
            "total_view": 4767,
            "visible": true,
            "total_comments": 1,
            "is_muted": false,
            "is_mypixiv_only": false,
            "is_x_restricted": false
        },
        {
            "etc": "etc"
        }
    ],
    "next_url": "https://app-api.pixiv.net/v1/novel/follow?restrict=public&offset=30"
}
```

## https://app-api.pixiv.net/v1/novel/mypixiv

Retrieves a list of newly uploaded novels from users added to my pixiv.

**Requires authorisation header**

**GET request**

## https://app-api.pixiv.net/v1/trending-tags/illust

Retrieves a list of currently trending illustration/manga tags.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`

### Example Response

**Parameters**

filter - `for_android`

**Response**

```json
{
    "trend_tags": [
        {
            "tag": "アイドルマスターシンデレラガールズ",
            "translated_name": "The Idolmaster: Cinderella Girls",
            "illust": {
                "id": 79252210,
                "title": "りあむちゃん",
                "type": "illust",
                "image_urls": {
                    "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/02/03/01/22/43/79252210_p0_square1200.jpg",
                    "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/02/03/01/22/43/79252210_p0_master1200.jpg",
                    "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/02/03/01/22/43/79252210_p0_master1200.jpg"
                },
                "caption": "",
                "restrict": 0,
                "user": {
                    "id": 28145748,
                    "name": "なび",
                    "account": "uz02",
                    "profile_image_urls": {
                        "medium": "https://i.pximg.net/user-profile/img/2019/08/15/14/49/40/16145606_0f97899844f7ce9d4819f3b2e4f03da3_170.png"
                    },
                    "is_followed": false
                },
                "tags": [
                    {
                        "name": "アイドルマスターシンデレラガールズ",
                        "translated_name": "The Idolmaster: Cinderella Girls"
                    },
                    {
                        "name": "夢見りあむ",
                        "translated_name": "Riamu Yumemi"
                    },
                    {
                        "name": "女の子",
                        "translated_name": "girl"
                    },
                    {
                        "name": "アイマス1000users入り",
                        "translated_name": "The Idolmaster 1000+ bookmarks"
                    },
                    {
                        "name": "着衣巨乳",
                        "translated_name": "clothed breasts"
                    }
                ],
                "tools": [
                    "CLIP STUDIO PAINT"
                ],
                "create_date": "2020-02-03T01:22:43+09:00",
                "page_count": 1,
                "width": 1000,
                "height": 1415,
                "sanity_level": 2,
                "x_restrict": 0,
                "series": null,
                "meta_single_page": {
                    "original_image_url": "https://i.pximg.net/img-original/img/2020/02/03/01/22/43/79252210_p0.png"
                },
                "meta_pages": [],
                "total_view": 23287,
                "total_bookmarks": 6350,
                "is_bookmarked": false,
                "visible": true,
                "is_muted": false
            }
        },
        {
            "etc": "etc"
        }
    ]
}
```

## https://app-api.pixiv.net/v1/trending-tags/novel

Retrieves a list of trending novel tags.

**Requires authorisation header**

**GET request**

### Example Response

```json
{
    "trend_tags": [
        {
            "tag": "不死川実弥",
            "translated_name": "Sanemi Shinazugawa",
            "illust": {
                "id": 77948447,
                "title": "風柱と水柱の喧嘩を止める恋柱漫画",
                "type": "manga",
                "image_urls": {
                    "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2019/11/23/13/16/55/77948447_p0_square1200.jpg",
                    "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/11/23/13/16/55/77948447_p0_master1200.jpg",
                    "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/11/23/13/16/55/77948447_p0_master1200.jpg"
                },
                "caption": "もし緊急柱合会議で喧嘩が始まってしまってたら。<br />多分擦り傷……で済んだ…と思います。<br />このあと悲鳴嶼さんが何事もなかったかのように柱稽古の提案を始めたのでうやむやになった。",
                "restrict": 0,
                "user": {
                    "id": 17398459,
                    "name": "壱松",
                    "account": "odoro_lol",
                    "profile_image_urls": {
                        "medium": "https://i.pximg.net/user-profile/img/2018/11/02/11/36/43/14969477_a8a4f7a955f4bc952bfac720e4e4197b_170.png"
                    },
                    "is_followed": false
                },
                "tags": [
                    {
                        "name": "漫画",
                        "translated_name": "manga"
                    },
                    {
                        "name": "鬼滅の刃",
                        "translated_name": "Demon Slayer: Kimetsu no Yaiba"
                    },
                    {
                        "name": "甘露寺蜜璃",
                        "translated_name": "Mitsuri Kanjiro"
                    },
                    {
                        "name": "不死川実弥",
                        "translated_name": "Sanemi Shinazugawa"
                    },
                    {
                        "name": "冨岡義勇",
                        "translated_name": "Giyu Tomioka"
                    },
                    {
                        "name": "ありそうで困る",
                        "translated_name": null
                    },
                    {
                        "name": "女子力(物理)",
                        "translated_name": "physical girl power"
                    },
                    {
                        "name": "甘露寺物理",
                        "translated_name": null
                    },
                    {
                        "name": "鬼滅の刃40000users入り",
                        "translated_name": null
                    },
                    {
                        "name": "喧嘩(一方的)",
                        "translated_name": null
                    }
                ],
                "tools": [],
                "create_date": "2019-11-23T13:16:55+09:00",
                "page_count": 2,
                "width": 1433,
                "height": 1012,
                "sanity_level": 2,
                "x_restrict": 0,
                "series": null,
                "meta_single_page": {},
                "meta_pages": [
                    {
                        "image_urls": {
                            "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/11/23/13/16/55/77948447_p0_square1200.jpg",
                            "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/11/23/13/16/55/77948447_p0_master1200.jpg",
                            "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/11/23/13/16/55/77948447_p0_master1200.jpg",
                            "original": "https://i.pximg.net/img-original/img/2019/11/23/13/16/55/77948447_p0.jpg"
                        }
                    },
                    {
                        "image_urls": {
                            "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2019/11/23/13/16/55/77948447_p1_square1200.jpg",
                            "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2019/11/23/13/16/55/77948447_p1_master1200.jpg",
                            "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2019/11/23/13/16/55/77948447_p1_master1200.jpg",
                            "original": "https://i.pximg.net/img-original/img/2019/11/23/13/16/55/77948447_p1.jpg"
                        }
                    }
                ],
                "total_view": 600129,
                "total_bookmarks": 48058,
                "is_bookmarked": false,
                "visible": true,
                "is_muted": false
            }
        },
        {
            "etc": "etc"
        }
    ]
}
```