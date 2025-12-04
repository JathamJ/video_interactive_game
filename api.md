# 获取视频信息接口

```
curl --location --request GET 'http://127.0.0.1:8101/v1/game/video?gameId=1&sceneId=1'
```

### 返回
{
    "code": 200,
    "msg": "success",
    "data": {
        "id": 2,
        "video": "https://qn.gzquan.cn/1.mp4-sole.m3u8",
        "title": "",
        "brief": "",
        "options": [
            {
                "id": 3,
                "value": "'嫂嫂不必多礼。我既归家，自当护兄长周全。'",
                "audio": "",
                "video": "https://qn.gzquan.cn/game_start.mp4-sole.m3u8",
                "title": ""
            },
            {
                "id": 4,
                "value": "听闻嫂嫂原是大户人家使女，怎会嫁与我兄？",
                "audio": "",
                "video": "https://qn.gzquan.cn/1.mp4-sole.m3u8",
                "title": ""
            },
            {
                "id": 5,
                "value": "'家中可有酒？我想与大哥对饮叙旧。'",
                "audio": "",
                "video": "https://qn.gzquan.cn/1.mp4-sole.m3u8",
                "title": ""
            }
        ]
    }
}