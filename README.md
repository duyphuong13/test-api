# 400

|                                       |                                                 |
| ------------------------------------- | ----------------------------------------------- |
| Resource                              | Get all vehicles by country                                         |
| Path                                  | vehicles/                                           |
| Error Type                            | [system]                                       |
| Response Code                         | 400                                              |
| Error Code                            | 400.Get all vehicles by country.[error code count index]                                     |
| Error Message                         | [error message] |

## Meaning
The request is invalid, malformed or does not meet mandatory field requirements.

## Response


#### Payload 



| Parameter | Meaning | Sample | PII | Unique Identify | Mandatory | Default | Details |
| :----- | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :----- |
| error |  -  | bad_request  |  No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |
| message |  -  | Bad Request - Id is invalid.  |  No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |




#### Json sample
```
{
  "error": "bad_request",
  "message": "Bad Request - Id is invalid."
}
```



#### Json Schema
```
{
  "type": "object",
  "$schema": "http://json-schema.org/schema#",
  "properties": {
    "error": {
      "$id": "/properties/error",
      "type": "string",
      "title": "error",
      "examples": [
        "bad_request"
      ]
    },
    "message": {
      "$id": "/properties/message",
      "type": "string",
      "title": "message",
      "examples": [
        "Bad Request - Id is invalid."
      ]
    }
  }
}
```

