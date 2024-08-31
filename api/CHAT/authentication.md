> [English](./authentication.md) | [中文](./authentication_cn.md)

### POST /application/authentication

## Description

Application Authentication

## Request Parameters

| Field        | Type   | Required | Description        |
| ------------ | ------ | -------- | ------------------ |
| access_token | string | Yes      | Widget session ID   |

```json
{
   "access_token":"123"
}
```

# Response Parameters

| Field  | Name   | Type   | Description                                            |
| ------ | ------ | ------ | --------------------------------------------  |
| code   | code | int32  |  200 indicates success
| message | message   | string | A description detailing the success or failure  |
| data   | data | string | The specific data format is defined by each API     |

```json
{
    "code":200,
    "message":"Success",
    "data": "eyjh......",
}
```
