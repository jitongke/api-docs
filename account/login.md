# 登录

##请求：
```
{
  "cmd": "account/login",
  "cityId": "31",
  "parameters": {
    "phone": "12333334444",
  	"password": "1111"
  }

}
```
### 请求参数说明
| 参数名称 | 是否必填 | 参数说明 |
| -- | -- | -- |
| cityId | 否 | 地域code |
| phone | 是 | 手机号 |
| password | 是 | 密码 |

响应：
```
{
    "messageId": null,
    "requestId": "1eca6cc5-a4b0-11e5-b6cf-0050568b147d",
    "error": null,
    "statusCode": 200,
    "cmd": "account/login",
    "response": {
        "accountId": 26,
        "token": "f982fa37e1cc45608047b20ce5792e7e",
        "status": "1"
    },
    "responseTime": "2015-12-17 19:20:18",
    "responseTimestamp": 0,
    "duration": 14721,
    "debugInfo": null,
    "clientIp": "10.250.103.11",
    "usedCache": false,
    "extraInfo": {
        "serverName": "10.10.47.4"
    },
    "auth": {}
}
```
