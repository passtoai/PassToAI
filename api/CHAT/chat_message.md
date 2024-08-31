> [English](./chat_message.md) | [中文](./chat_message_cn.md)


### GET application/chat_message/{chat_id}

## Description

Conversation

## Request Parameters

| Field     | Type    | Required | Description              |
| --------- | ------- | -------- | ------------------------ |
| message   | string  | Yes      | The question             |
| re_chat   | boolean | No       | Regenerate response      |
| stream    | boolean | No       | Streamed response        |

```json
{
  "message": "string",
  "re_chat": false,
  "stream": true
}
```

# Response

| Field    | Name	   | Type	    | Description                                           |
| ------ | ------ | ------ | --------------------------------------------  |
| application_id   | Code | int32   |  200 indicates success                       |
| desc | Message   | string | A description detailing the success or failure                          |
| data   | Data	 | string |                     |

```json
{
    "code": 200,
    "message": "Success",
    "data": ""
}
```
