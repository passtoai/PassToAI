### GET /application/profile

## 說明

獲取應用信息


# 應答

| 字段    | 名称   | 類型    | 說明                                           |
| ------ | ------ | ------ | --------------------------------------------  |
| application_type   | 协议号 | int32   |  200代表成功                       |
| desc | 消息   | string | 对成功或者失败具体的描述                          |
| data   | 數據體 | object |                     |

```json
{
    "code": 200,
    "message": "成功",
    "data": {
        "id": "a46c9086-4a4c-11ef-9012-0242ac110002",
        "name": "xxxxx",
        "desc": "",
        "prologue": "xxxx",
        "icon": "/ui/favicon.ico",
        "application_type": 0,
        "show_source": false,
        "multiple_rounds_dialogue": true
    }
}
```
