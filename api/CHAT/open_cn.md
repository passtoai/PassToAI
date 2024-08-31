> [English](./open.md) | [中文](./open_cn.md)

### GET /application/{application_id}/chat/open

## 說明

創建應用會話ID

## 請求參數

|字段|類型|必填項|說明|
|--- |--- |--- |--- |
|application_id|string|是|應用id|

```json
{
   "application_id":"123"
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
    "data": "63e5b956-4a57-11ef-968c-0242ac110002"
}
```
