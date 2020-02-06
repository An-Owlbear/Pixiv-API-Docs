# Series

## https://app-api.pixiv.net/v1/illust-series/illust

View information about the series an illustration/manga belongs to.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`<br>
illust_id - `[illust_id]`

### Example Response

**Parameters**

filter - `for_android`<br>
illust_id - `79070294`

**Response**

```json
{
    "illust_series_detail": {
        "id": 21859,
        "title": "先輩がうざい後輩の話",
        "caption": "先輩がうざい後輩の話です。\nいつも閲覧いただきありがとうございます！\n\nTwitter:@mashiron1020",
        "cover_image_urls": {
            "medium": "https://i.pximg.net/c/782x410_80_a2_g5/illust-series-cover-original/img/2018/03/15/08/12/21/ARkQKvIW9ZBHVvihK8L5DAVuZ26tGSUP.jpg"
        },
        "series_work_count": 112,
        "create_date": "2017-10-22T14:07:42+09:00",
        "width": 3439,
        "height": 1611,
        "user": {
            "id": 10509347,
            "name": "しろまんた",
            "account": "misomisomiso1020",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2018/04/27/14/31/50/14147053_e9dc153993f26de401c0359022455531_170.jpg"
            },
            "is_followed": false
        }
    },
    "illust_series_context": {
        "content_order": 112,
        "prev": {
            "id": 78947029,
            "title": "先輩がうざい後輩の話【99】",
            "type": "manga",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg"
            },
            "caption": "いつもコメントやタグ本当にありがとうございます！<br />とても励みになっております！<br /><br />ラインスタンプ作りました。<br /><a href=\"https://line.me/S/shop/sticker/author/195362\" target=\"_blank\">https://line.me/S/shop/sticker/author/195362</a><br /><br />単行本が出てます。こちらには載っていないお話が結構あります。<br />1巻　<a href=\"http://amzn.asia/bGjatHL\" target=\"_blank\">http://amzn.asia/bGjatHL</a><br />2巻　<a href=\"http://amzn.asia/d/8TFo66h\" target=\"_blank\">http://amzn.asia/d/8TFo66h</a><br />3巻　<a href=\"https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2</a><br />1～3巻せっと　<a href=\"https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2\" target=\"_blank\">https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2</a><br /><br />4巻販売しております！よろしければ！<br /><a href=\"https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE</a>",
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
                    "name": "漫画",
                    "translated_name": "manga"
                },
                {
                    "name": "先輩がうざい後輩の話",
                    "translated_name": "My Senpai Is Annoying"
                },
                {
                    "name": "神様も焦らされるふたりの話",
                    "translated_name": null
                },
                {
                    "name": "幸運値がすごい同僚の話",
                    "translated_name": null
                },
                {
                    "name": "おみくじがペアルック",
                    "translated_name": null
                },
                {
                    "name": "過去に何があった?",
                    "translated_name": null
                },
                {
                    "name": "大凶って少なすぎて逆にラッキーらしいよ",
                    "translated_name": null
                },
                {
                    "name": "本当となりを見よ",
                    "translated_name": null
                }
            ],
            "tools": [],
            "create_date": "2020-01-17T19:00:10+09:00",
            "page_count": 4,
            "width": 1720,
            "height": 2428,
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
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p0.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p1.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p2_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p2_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p2_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p2.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p3_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p3_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p3_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p3.jpg"
                    }
                }
            ],
            "total_view": 188737,
            "total_bookmarks": 7938,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false,
            "total_comments": 196
        },
        "next": null
    }
}{
    "illust_series_detail": {
        "id": 21859,
        "title": "先輩がうざい後輩の話",
        "caption": "先輩がうざい後輩の話です。\nいつも閲覧いただきありがとうございます！\n\nTwitter:@mashiron1020",
        "cover_image_urls": {
            "medium": "https://i.pximg.net/c/782x410_80_a2_g5/illust-series-cover-original/img/2018/03/15/08/12/21/ARkQKvIW9ZBHVvihK8L5DAVuZ26tGSUP.jpg"
        },
        "series_work_count": 112,
        "create_date": "2017-10-22T14:07:42+09:00",
        "width": 3439,
        "height": 1611,
        "user": {
            "id": 10509347,
            "name": "しろまんた",
            "account": "misomisomiso1020",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2018/04/27/14/31/50/14147053_e9dc153993f26de401c0359022455531_170.jpg"
            },
            "is_followed": false
        }
    },
    "illust_series_context": {
        "content_order": 112,
        "prev": {
            "id": 78947029,
            "title": "先輩がうざい後輩の話【99】",
            "type": "manga",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg"
            },
            "caption": "いつもコメントやタグ本当にありがとうございます！<br />とても励みになっております！<br /><br />ラインスタンプ作りました。<br /><a href=\"https://line.me/S/shop/sticker/author/195362\" target=\"_blank\">https://line.me/S/shop/sticker/author/195362</a><br /><br />単行本が出てます。こちらには載っていないお話が結構あります。<br />1巻　<a href=\"http://amzn.asia/bGjatHL\" target=\"_blank\">http://amzn.asia/bGjatHL</a><br />2巻　<a href=\"http://amzn.asia/d/8TFo66h\" target=\"_blank\">http://amzn.asia/d/8TFo66h</a><br />3巻　<a href=\"https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2</a><br />1～3巻せっと　<a href=\"https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2\" target=\"_blank\">https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2</a><br /><br />4巻販売しております！よろしければ！<br /><a href=\"https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE</a>",
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
                    "name": "漫画",
                    "translated_name": "manga"
                },
                {
                    "name": "先輩がうざい後輩の話",
                    "translated_name": "My Senpai Is Annoying"
                },
                {
                    "name": "神様も焦らされるふたりの話",
                    "translated_name": null
                },
                {
                    "name": "幸運値がすごい同僚の話",
                    "translated_name": null
                },
                {
                    "name": "おみくじがペアルック",
                    "translated_name": null
                },
                {
                    "name": "過去に何があった?",
                    "translated_name": null
                },
                {
                    "name": "大凶って少なすぎて逆にラッキーらしいよ",
                    "translated_name": null
                },
                {
                    "name": "本当となりを見よ",
                    "translated_name": null
                }
            ],
            "tools": [],
            "create_date": "2020-01-17T19:00:10+09:00",
            "page_count": 4,
            "width": 1720,
            "height": 2428,
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
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p0.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p1.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p2_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p2_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p2_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p2.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p3_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p3_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p3_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p3.jpg"
                    }
                }
            ],
            "total_view": 188737,
            "total_bookmarks": 7938,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false,
            "total_comments": 196
        },
        "next": null
    }
}{
    "illust_series_detail": {
        "id": 21859,
        "title": "先輩がうざい後輩の話",
        "caption": "先輩がうざい後輩の話です。\nいつも閲覧いただきありがとうございます！\n\nTwitter:@mashiron1020",
        "cover_image_urls": {
            "medium": "https://i.pximg.net/c/782x410_80_a2_g5/illust-series-cover-original/img/2018/03/15/08/12/21/ARkQKvIW9ZBHVvihK8L5DAVuZ26tGSUP.jpg"
        },
        "series_work_count": 112,
        "create_date": "2017-10-22T14:07:42+09:00",
        "width": 3439,
        "height": 1611,
        "user": {
            "id": 10509347,
            "name": "しろまんた",
            "account": "misomisomiso1020",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2018/04/27/14/31/50/14147053_e9dc153993f26de401c0359022455531_170.jpg"
            },
            "is_followed": false
        }
    },
    "illust_series_context": {
        "content_order": 112,
        "prev": {
            "id": 78947029,
            "title": "先輩がうざい後輩の話【99】",
            "type": "manga",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg"
            },
            "caption": "いつもコメントやタグ本当にありがとうございます！<br />とても励みになっております！<br /><br />ラインスタンプ作りました。<br /><a href=\"https://line.me/S/shop/sticker/author/195362\" target=\"_blank\">https://line.me/S/shop/sticker/author/195362</a><br /><br />単行本が出てます。こちらには載っていないお話が結構あります。<br />1巻　<a href=\"http://amzn.asia/bGjatHL\" target=\"_blank\">http://amzn.asia/bGjatHL</a><br />2巻　<a href=\"http://amzn.asia/d/8TFo66h\" target=\"_blank\">http://amzn.asia/d/8TFo66h</a><br />3巻　<a href=\"https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2</a><br />1～3巻せっと　<a href=\"https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2\" target=\"_blank\">https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2</a><br /><br />4巻販売しております！よろしければ！<br /><a href=\"https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE</a>",
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
                    "name": "漫画",
                    "translated_name": "manga"
                },
                {
                    "name": "先輩がうざい後輩の話",
                    "translated_name": "My Senpai Is Annoying"
                },
                {
                    "name": "神様も焦らされるふたりの話",
                    "translated_name": null
                },
                {
                    "name": "幸運値がすごい同僚の話",
                    "translated_name": null
                },
                {
                    "name": "おみくじがペアルック",
                    "translated_name": null
                },
                {
                    "name": "過去に何があった?",
                    "translated_name": null
                },
                {
                    "name": "大凶って少なすぎて逆にラッキーらしいよ",
                    "translated_name": null
                },
                {
                    "name": "本当となりを見よ",
                    "translated_name": null
                }
            ],
            "tools": [],
            "create_date": "2020-01-17T19:00:10+09:00",
            "page_count": 4,
            "width": 1720,
            "height": 2428,
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
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p0.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p1.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p2_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p2_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p2_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p2.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p3_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p3_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p3_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p3.jpg"
                    }
                }
            ],
            "total_view": 188737,
            "total_bookmarks": 7938,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false,
            "total_comments": 196
        },
        "next": null
    }
}{
    "illust_series_detail": {
        "id": 21859,
        "title": "先輩がうざい後輩の話",
        "caption": "先輩がうざい後輩の話です。\nいつも閲覧いただきありがとうございます！\n\nTwitter:@mashiron1020",
        "cover_image_urls": {
            "medium": "https://i.pximg.net/c/782x410_80_a2_g5/illust-series-cover-original/img/2018/03/15/08/12/21/ARkQKvIW9ZBHVvihK8L5DAVuZ26tGSUP.jpg"
        },
        "series_work_count": 112,
        "create_date": "2017-10-22T14:07:42+09:00",
        "width": 3439,
        "height": 1611,
        "user": {
            "id": 10509347,
            "name": "しろまんた",
            "account": "misomisomiso1020",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2018/04/27/14/31/50/14147053_e9dc153993f26de401c0359022455531_170.jpg"
            },
            "is_followed": false
        }
    },
    "illust_series_context": {
        "content_order": 112,
        "prev": {
            "id": 78947029,
            "title": "先輩がうざい後輩の話【99】",
            "type": "manga",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg"
            },
            "caption": "いつもコメントやタグ本当にありがとうございます！<br />とても励みになっております！<br /><br />ラインスタンプ作りました。<br /><a href=\"https://line.me/S/shop/sticker/author/195362\" target=\"_blank\">https://line.me/S/shop/sticker/author/195362</a><br /><br />単行本が出てます。こちらには載っていないお話が結構あります。<br />1巻　<a href=\"http://amzn.asia/bGjatHL\" target=\"_blank\">http://amzn.asia/bGjatHL</a><br />2巻　<a href=\"http://amzn.asia/d/8TFo66h\" target=\"_blank\">http://amzn.asia/d/8TFo66h</a><br />3巻　<a href=\"https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2</a><br />1～3巻せっと　<a href=\"https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2\" target=\"_blank\">https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2</a><br /><br />4巻販売しております！よろしければ！<br /><a href=\"https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE</a>",
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
                    "name": "漫画",
                    "translated_name": "manga"
                },
                {
                    "name": "先輩がうざい後輩の話",
                    "translated_name": "My Senpai Is Annoying"
                },
                {
                    "name": "神様も焦らされるふたりの話",
                    "translated_name": null
                },
                {
                    "name": "幸運値がすごい同僚の話",
                    "translated_name": null
                },
                {
                    "name": "おみくじがペアルック",
                    "translated_name": null
                },
                {
                    "name": "過去に何があった?",
                    "translated_name": null
                },
                {
                    "name": "大凶って少なすぎて逆にラッキーらしいよ",
                    "translated_name": null
                },
                {
                    "name": "本当となりを見よ",
                    "translated_name": null
                }
            ],
            "tools": [],
            "create_date": "2020-01-17T19:00:10+09:00",
            "page_count": 4,
            "width": 1720,
            "height": 2428,
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
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p0.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p1.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p2_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p2_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p2_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p2.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/17/19/00/10/78947029_p3_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/17/19/00/10/78947029_p3_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/17/19/00/10/78947029_p3_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/17/19/00/10/78947029_p3.jpg"
                    }
                }
            ],
            "total_view": 188737,
            "total_bookmarks": 7938,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false,
            "total_comments": 196
        },
        "next": null
    }
}
```

## https://app-api.pixiv.net/v1/illust/series

Views a series of illustrations from the given id.

**Requires authorisation header**

**GET request**

### Parameters

filter - `for_android`<br>
illust_series_id - `[illust_series_id]`

### Example Response

**Parameters**

filter - `for_android`<br>
illust_series_id - `21859`

**Response**

```json
{
    "illust_series_detail": {
        "id": 21859,
        "title": "先輩がうざい後輩の話",
        "caption": "先輩がうざい後輩の話です。\nいつも閲覧いただきありがとうございます！\n\nTwitter:@mashiron1020",
        "cover_image_urls": {
            "medium": "https://i.pximg.net/c/782x410_80_a2_g5/illust-series-cover-original/img/2018/03/15/08/12/21/ARkQKvIW9ZBHVvihK8L5DAVuZ26tGSUP.jpg"
        },
        "series_work_count": 112,
        "create_date": "2017-10-22T14:07:42+09:00",
        "width": 3439,
        "height": 1611,
        "user": {
            "id": 10509347,
            "name": "しろまんた",
            "account": "misomisomiso1020",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2018/04/27/14/31/50/14147053_e9dc153993f26de401c0359022455531_170.jpg"
            },
            "is_followed": false
        }
    },
    "illust_series_first_illust": {
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
        "total_view": 1014393,
        "total_bookmarks": 49067,
        "is_bookmarked": false,
        "visible": true,
        "is_muted": false,
        "total_comments": 185
    },
    "illusts": [
        {
            "id": 79070294,
            "title": "先輩がうざい後輩の話【100】",
            "type": "manga",
            "image_urls": {
                "square_medium": "https://i.pximg.net/c/540x540_10_webp/img-master/img/2020/01/24/19/00/04/79070294_p0_square1200.jpg",
                "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/24/19/00/04/79070294_p0_master1200.jpg",
                "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/24/19/00/04/79070294_p0_master1200.jpg"
            },
            "caption": "💯<br /><br />気が付けば100話になっておりました。<br />ここまで楽しく描かせていただけているのはひとえに応援してくださっている皆様のおかげです。<br />本当にありがとうございます。<br />これからも仲良くしていただけると幸いです・・・！<br /><br />ラインスタンプ作りました。<br /><a href=\"https://line.me/S/shop/sticker/author/195362\" target=\"_blank\">https://line.me/S/shop/sticker/author/195362</a><br /><br />単行本が出てます。こちらには載っていないお話が結構あります。<br />1巻　<a href=\"http://amzn.asia/bGjatHL\" target=\"_blank\">http://amzn.asia/bGjatHL</a><br />2巻　<a href=\"http://amzn.asia/d/8TFo66h\" target=\"_blank\">http://amzn.asia/d/8TFo66h</a><br />3巻　<a href=\"https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020264/ref=cm_sw_r_tw_dp_U_x_J2uGCbZKV4SX2</a><br />1～3巻せっと　<a href=\"https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2\" target=\"_blank\">https://www.amazon.co.jp/dp/B07P5N8WWX/ref=cm_sw_r_tw_dp_U_x_j4uGCb0E90GE2</a><br /><br />4巻販売しております！よろしければ！<br /><a href=\"https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE\" target=\"_blank\">https://www.amazon.co.jp/dp/4758020515/ref=cm_sw_em_r_mt_dp_U_KaqvDbJ2B27EE</a>",
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
                    "name": "漫画",
                    "translated_name": "manga"
                },
                {
                    "name": "先輩がうざい後輩の話",
                    "translated_name": "My Senpai Is Annoying"
                },
                {
                    "name": "本当は先輩にずっと守ってほしい後輩の話",
                    "translated_name": null
                },
                {
                    "name": "守りたい、この笑顔",
                    "translated_name": "I want to protect that smile"
                },
                {
                    "name": "何も心配しなくていい",
                    "translated_name": null
                },
                {
                    "name": "お前が一生守るんだよ",
                    "translated_name": null
                }
            ],
            "tools": [],
            "create_date": "2020-01-24T19:00:04+09:00",
            "page_count": 4,
            "width": 1720,
            "height": 2428,
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
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/24/19/00/04/79070294_p0_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/24/19/00/04/79070294_p0_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/24/19/00/04/79070294_p0_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/24/19/00/04/79070294_p0.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/24/19/00/04/79070294_p1_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/24/19/00/04/79070294_p1_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/24/19/00/04/79070294_p1_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/24/19/00/04/79070294_p1.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/24/19/00/04/79070294_p2_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/24/19/00/04/79070294_p2_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/24/19/00/04/79070294_p2_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/24/19/00/04/79070294_p2.jpg"
                    }
                },
                {
                    "image_urls": {
                        "square_medium": "https://i.pximg.net/c/360x360_10_webp/img-master/img/2020/01/24/19/00/04/79070294_p3_square1200.jpg",
                        "medium": "https://i.pximg.net/c/540x540_70/img-master/img/2020/01/24/19/00/04/79070294_p3_master1200.jpg",
                        "large": "https://i.pximg.net/c/600x1200_90_webp/img-master/img/2020/01/24/19/00/04/79070294_p3_master1200.jpg",
                        "original": "https://i.pximg.net/img-original/img/2020/01/24/19/00/04/79070294_p3.jpg"
                    }
                }
            ],
            "total_view": 149303,
            "total_bookmarks": 8997,
            "is_bookmarked": false,
            "visible": true,
            "is_muted": false
        },
    ],
    "next_url": "https://app-api.pixiv.net/v1/illust/series?filter=for_android&illust_series_id=21859&offset=30"
}
```

## https://app-api.pixiv.net/v2/novel/series

Retrieves the information of a novel series of the given id.

**Requires authorisation header**

**GET request**

### Parameters

series_id - `[series_id]`

### Example Response

**Parameters**

series_id - `1238664`

**Response**

```json
{
    "novel_series_detail": {
        "id": 1238664,
        "title": "アローラ！",
        "caption": "アローラ地方に新婚旅行にいくキバユウ",
        "is_original": false,
        "is_concluded": false,
        "content_count": 13,
        "total_character_count": 44907,
        "user": {
            "id": 3066912,
            "name": "ポプコ",
            "account": "fitomi",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2019/09/30/21/21/50/16351585_cdd91e7576dc53ab2c6e1bbcf9cdbd37_170.jpg"
            },
            "is_followed": false
        },
        "display_text": "アローラ地方に新婚旅行にいくキバユウ"
    },
    "novel_series_first_novel": {
        "id": 12248944,
        "title": "アローラ！vol.2",
        "caption": "女子会ってすごくダラダラしますね。ええ、本当に。",
        "restrict": 0,
        "x_restrict": 0,
        "is_original": false,
        "image_urls": {
            "square_medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_128x128.jpg",
            "medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_176mw.jpg",
            "large": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_240mw.jpg"
        },
        "create_date": "2020-01-19T10:01:21+09:00",
        "tags": [
            {
                "name": "キバユウ",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "ポケモン剣盾",
                "translated_name": "Pokémon Sword and Shield",
                "added_by_uploaded_user": true
            },
            {
                "name": "女子会",
                "translated_name": null,
                "added_by_uploaded_user": true
            }
        ],
        "page_count": 2,
        "text_length": 2832,
        "user": {
            "id": 3066912,
            "name": "ポプコ",
            "account": "fitomi",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2019/09/30/21/21/50/16351585_cdd91e7576dc53ab2c6e1bbcf9cdbd37_170.jpg"
            },
            "is_followed": false
        },
        "series": {
            "id": 1238664,
            "title": "アローラ！"
        },
        "is_bookmarked": false,
        "total_bookmarks": 39,
        "total_view": 802,
        "visible": true,
        "total_comments": 0,
        "is_muted": false,
        "is_mypixiv_only": false,
        "is_x_restricted": false
    },
    "novel_series_latest_novel": {
        "id": 12280943,
        "title": "アローラ！最終話",
        "caption": "やっとアーモンドの花から始まったストーリーが終わりました。読了してくださった皆様に感謝です。",
        "restrict": 0,
        "x_restrict": 0,
        "is_original": false,
        "image_urls": {
            "square_medium": "https://i.pximg.net/c/128x128/novel-cover-master/img/2020/01/26/16/26/45/12280943_fe8c7e4d5ead00630acc045ec6118cf3_square1200.jpg",
            "medium": "https://i.pximg.net/c/176x352/novel-cover-master/img/2020/01/26/16/26/45/12280943_fe8c7e4d5ead00630acc045ec6118cf3_master1200.jpg",
            "large": "https://i.pximg.net/c/240x480_80/novel-cover-master/img/2020/01/26/16/26/45/12280943_fe8c7e4d5ead00630acc045ec6118cf3_master1200.jpg"
        },
        "create_date": "2020-01-26T16:26:45+09:00",
        "tags": [
            {
                "name": "キバユウ",
                "translated_name": null,
                "added_by_uploaded_user": true
            },
            {
                "name": "ポケモン剣盾",
                "translated_name": "Pokémon Sword and Shield",
                "added_by_uploaded_user": true
            }
        ],
        "page_count": 6,
        "text_length": 3043,
        "user": {
            "id": 3066912,
            "name": "ポプコ",
            "account": "fitomi",
            "profile_image_urls": {
                "medium": "https://i.pximg.net/user-profile/img/2019/09/30/21/21/50/16351585_cdd91e7576dc53ab2c6e1bbcf9cdbd37_170.jpg"
            },
            "is_followed": false
        },
        "series": {
            "id": 1238664,
            "title": "アローラ！"
        },
        "is_bookmarked": false,
        "total_bookmarks": 15,
        "total_view": 365,
        "visible": true,
        "total_comments": 2,
        "is_muted": false,
        "is_mypixiv_only": false,
        "is_x_restricted": false
    },
    "novels": [
        {
            "id": 12248944,
            "title": "アローラ！vol.2",
            "caption": "女子会ってすごくダラダラしますね。ええ、本当に。",
            "restrict": 0,
            "x_restrict": 0,
            "is_original": false,
            "image_urls": {
                "square_medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_128x128.jpg",
                "medium": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_176mw.jpg",
                "large": "https://s.pximg.net/common/images/novel_thumb/novel_thumb_0_240mw.jpg"
            },
            "create_date": "2020-01-19T10:01:21+09:00",
            "tags": [
                {
                    "name": "キバユウ",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                },
                {
                    "name": "ポケモン剣盾",
                    "translated_name": "Pokémon Sword and Shield",
                    "added_by_uploaded_user": true
                },
                {
                    "name": "女子会",
                    "translated_name": null,
                    "added_by_uploaded_user": true
                }
            ],
            "page_count": 2,
            "text_length": 2832,
            "user": {
                "id": 3066912,
                "name": "ポプコ",
                "account": "fitomi",
                "profile_image_urls": {
                    "medium": "https://i.pximg.net/user-profile/img/2019/09/30/21/21/50/16351585_cdd91e7576dc53ab2c6e1bbcf9cdbd37_170.jpg"
                },
                "is_followed": false
            },
            "series": {
                "id": 1238664,
                "title": "アローラ！"
            },
            "is_bookmarked": false,
            "total_bookmarks": 39,
            "total_view": 802,
            "visible": true,
            "total_comments": 0,
            "is_muted": false,
            "is_mypixiv_only": false,
            "is_x_restricted": false
        },
    ],
    "next_url": null
}
```
