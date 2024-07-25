### GET application/chat_message/{chat_id}

## 說明

對話

## 請求參數

|字段|類型|必填項|說明|
|--- |--- |--- |--- |
|message|string|是|问题|
|re_chat|boolean|否|重新生成|
|stream|boolean|否|流式回答|


```json
{
  "message": "string",
  "re_chat": false,
  "stream": true
}
```

# 應答

| 字段    | 名称   | 類型    | 說明                                           |
| ------ | ------ | ------ | --------------------------------------------  |
| application_id   | 协议号 | int32   |  200代表成功                       |
| desc | 消息   | string | 对成功或者失败具体的描述                          |
| data   | 數據體 | string |                     |

```json
{
    "code": 200,
    "message": "成功",
    "data": ""
}
```
