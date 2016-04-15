#Data Format

```json
{

    "_index": "twitter",
    "_type": "logs",
    "_id": "AVQYVKfvB8swVKGYDrXO",
    "_version": 1,
    "_score": 1,
    "_source": {
        "created_at": "Fri Apr 15 05:11:20 +0000 2016",
        "id": 720841919484432400,
        "id_str": "720841919484432384",
        "text": "#TIME Nepal Earthquake: New photos by James Nachtwey, a year after the earthquake https://t.co/LhTInyTwGU",
        "source": "<a href="http://ifttt.com" rel="nofollow">IFTTT</a>",
        "truncated": false,
        "in_reply_to_status_id": null,
        "in_reply_to_status_id_str": null,
        "in_reply_to_user_id": null,
        "in_reply_to_user_id_str": null,
        "in_reply_to_screen_name": null,
        "user": {
            "id": 2737015671,
            "id_str": "2737015671",
            "name": "News Hunter",
            "screen_name": "TheBrkNews",
            "location": "Global",
            "url": "http://news.news.news",
            "description": "@BBCBreaking @CNNbrk @NYTimes @BreakingNews @BBCWorld @CNN @TIME @ESPN @PBNSIR @ABC @ap @TheEconomist @WashingtonPost @BBCNews @ENews @ANI_news @XHNews @AJENews",
            "protected": false,
            "verified": false,
            "followers_count": 515,
            "friends_count": 81,
            "listed_count": 295,
            "favourites_count": 1,
            "statuses_count": 590887,
            "created_at": "Fri Aug 08 08:10:58 +0000 2014",
            "utc_offset": null,
            "time_zone": null,
            "geo_enabled": false,
            "lang": "en",
            "contributors_enabled": false,
            "is_translator": false,
            "profile_background_color": "C0DEED",
            "profile_background_image_url": "http://abs.twimg.com/images/themes/theme1/bg.png",
            "profile_background_image_url_https": "https://abs.twimg.com/images/themes/theme1/bg.png",
            "profile_background_tile": false,
            "profile_link_color": "0084B4",
            "profile_sidebar_border_color": "C0DEED",
            "profile_sidebar_fill_color": "DDEEF6",
            "profile_text_color": "333333",
            "profile_use_background_image": true,
            "profile_image_url": "http://pbs.twimg.com/profile_images/691967500666318848/3kbHSa1z_normal.jpg",
            "profile_image_url_https": "https://pbs.twimg.com/profile_images/691967500666318848/3kbHSa1z_normal.jpg",
            "profile_banner_url": "https://pbs.twimg.com/profile_banners/2737015671/1453812920",
            "default_profile": true,
            "default_profile_image": false,
            "following": null,
            "follow_request_sent": null,
            "notifications": null
        },
        "geo": null,
        "coordinates": null,
        "place": null,
        "contributors": null,
        "is_quote_status": false,
        "retweet_count": 0,
        "favorite_count": 0,
        "entities": {
            "hashtags": [
                {
                    "text": "TIME",
                    "indices": [
                        0
                        ,
                        5
                    ]
                }
            ],
            "urls": [
                {
                    "url": "https://t.co/LhTInyTwGU",
                    "expanded_url": "http://ti.me/1SFdCZn",
                    "display_url": "ti.me/1SFdCZn",
                    "indices": [
                        82
                        ,
                        105
                    ]
                }
            ],
            "user_mentions": [ ],
            "symbols": [ ]
        },
        "favorited": false,
        "retweeted": false,
        "possibly_sensitive": false,
        "filter_level": "low",
        "lang": "en",
        "timestamp_ms": "1460697080857",
        "@version": "1",
        "@timestamp": "2016-04-15T05:11:20.000Z"
    }

}
```

#Data Sources

The crawler is logstash to collect data.
 * Keywords : ["熊本地震" , "熊本" , "地震" , "日本" , "japan earthquake" ,"#日本大地震" ,"earthquake" , "japan" , "Japan"]
 


