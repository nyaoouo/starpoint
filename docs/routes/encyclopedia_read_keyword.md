# /latest/api/index.php/encyclopedia/read_keyword
                       
## Request
### Headers
```
Host: na.wdfp.kakaogames.com
Accept-Encoding: deflate, gzip
Accept: text/xml, application/xml, application/xhtml+xml, text/html;q=0.9, text/plain;q=0.8, text/css, image/png, image/jpeg, image/gif;q=0.8, application/x-shockwave-flash, video/mp4;q=0.9, flv-application/octet-stream;q=0.8, video/x-flv;q=0.7, audio/mp4, application/futuresplash, */*;q=0.5
User-Agent: Mozilla/5.0 (Android; U; en-US) AppleWebKit/533.19.4 (KHTML, like Gecko) AdobeAIR/51.0
x-flash-version: 51,0,1,1
Connection: Keep-Alive
Referer: app:/worldflipper_android_release.swf
Content-Type: application/x-www-form-urlencoded
PARAM: b0d56ad00674062ec4984535de0cc5729fb5e7f6
GAME-APP-ID: 297417490
SHORT_UDID: 461173975
UDID: BABE3558-59AA-47EB-513E-666932452A4BD405
RES_VER: 2.1.121
COUNTRY_CODE: us
APP_ID: 561429
KAKAO_PID: 984521158255
DEVICE_LANG: en
DEVICE_NAME: SM-S916U 14
APP_VER: 0.0.81
DEVICE: 2
Content-Length: 68
```

### Body
```
{
  "api_count": 33,
  "encyclopedia_ids": [
    133100501
  ],
  "viewer_id": 297417490
}
```

## Response
### Headers
```
Date: Thu, 13 Jun 2024 02:36:33 GMT
Content-Type: application/x-msgpack
Transfer-Encoding: chunked
Connection: keep-alive
Server: nginx
x-php-processing-time: 0.1131
x-result-code: 1
param: 9e8a5467e0b4fbbe8973196ab6425973ddc07a9d
```

### Body
```
{
  "data_headers": {
    "force_update": false,
    "asset_update": false,
    "short_udid": 461173975,
    "viewer_id": "<redacted>",
    "servertime": 1718246193,
    "result_code": 1
  },
  "data": {
    "encyclopedia_list": {
      "133100501": {
        "read": true
      }
    }
  }
}
```

