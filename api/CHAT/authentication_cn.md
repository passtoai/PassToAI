> [English](./authentication.md) | [中文](./authentication_cn.md)

### POST /application/authentication

## 說明

應用認證

## 請求參數

|字段|類型|必填項|說明|
|--- |--- |--- |--- |
|access_token|string|是|widget會話id|

```json
{
   "access_token":"123"
}
```

# 回應參數

| 字段    | 名称   | 類型   | 說明                                            |
| ------ | ------ | ------ | --------------------------------------------  |
| code   | 协议号 | int32  |  200代表成功
| message | 消息   | string | 对成功或者失败具体的描述                          |
| data   | 數據體 | string | 具体数据格式见各个接口定义                         |

```json
{
    "code":200,
    "message":"成功",
    "data": "eyjh......",
}
```
