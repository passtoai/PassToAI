> [English](./profile.md) | [中文](./profile_cn.md)

### GET /application/profile

## Description

Retrieve Application Information

## Response

| Field            | Name              | Type    | Description                                     |
| ---------------- | ----------------- | ------- | ----------------------------------------------- |
| application_type | Application Type  | int32   | 200 indicates success                           |
| desc             | Message           | string  | A description detailing the success or failure  |
| data             | Data              | object  |                                                 |

```json
{
    "code": 200,
    "message": "Success",
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
