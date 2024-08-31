> [English](./open.md) | [中文](./open_cn.md)

### GET /application/{application_id}/chat/open

## Description

Create Application Session ID

## Request Parameters

| Field          | Type   | Required | Description       |
| -------------- | ------ | -------- | ----------------- |
| application_id | string | Yes      | Application ID    |

```json
{
   "application_id": "123"
}

# Response

| Field    | Name   | Type    | Description                                           |
| ------ | ------ | ------ | --------------------------------------------  |
| application_id   | application_id | int32   |  200 indicates success                      |
| desc | Message   | string | A description detailing the success or failure    |
| data   | Data | string |                     |

```json
{
    "code": 200,
    "message": "Success",
    "data": "63e5b956-4a57-11ef-968c-0242ac110002"
}
```
