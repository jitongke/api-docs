# 注册

##请求参数：
```
{
  "cmd": "account/register",
  "cityId": "31", 
  "parameters": {
    "phone": "12333335555",
  	"password": "1111", 
  	"verification": "6666"
  }
}
```
### 请求参数说明
| 参数名称 | 是否必填 | 参数说明 |
| -- | -- | -- |
| cityId | 是 | 地域code |
| phone | 是 | 手机号 |
| password | 是 | 密码 |
| verification | 是 | 手机验证码 |

响应：
```
{
    "messageId": null,
    "requestId": "651ef689-a4b2-11e5-b6cf-0050568b147d",
    "error": null,
    "statusCode": 200,
    "cmd": "account/register",
    "response": 1,
    "responseTime": "2015-12-17 19:36:21",
    "responseTimestamp": 0,
    "duration": 202,
    "debugInfo": null,
    "clientIp": "10.250.103.11",
    "usedCache": false,
    "extraInfo": {
        "serverName": "10.10.47.4"
    },
    "auth": {}
}
```
