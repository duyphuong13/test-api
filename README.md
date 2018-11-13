# User Resources

GET /v2/vehicleManagement/vehicles/

## Description

Get a user to access to the platform, default permission is client member

|                                       |                                                 |
| ------------------------------------- | ----------------------------------------------- |
| HTTP Method                           | Get                                         |
| API                                   | Vehicle Management                                           |
| Api Version                           | 2.0.0.10                                         |
| Resource Version                      | 3                                               |
| Summary                               | Get all vehicles by country                                      |
| Description Version                   |  -  |
| Base Path                             | /v2/vehicleManagement/vehicles/                                     |
| Resource                              | Get all vehicles by country                                      |
| Endpoint URL                          | https://api-dev.universalgalaxy.co/v2/vehicleManagement/vehicles/              |
| Service Status                        | Unknown                                         |
| Legislative / Regulatory / Compliance |                                             |
| Firewalls Details                     |                                              |
| Security Certificate Details          |                                              |
| Vendor or Partner Considerations      |                                             |

## Request Payloads

### Request Header


N/A
---

### Query Params



| Parameter | Meaning | Sample | PII | Unique Identify | Mandatory | Default | Details |
| ------------- | :-----: | :-----: | :---: | :---------------: | :---------: | :-------: | ------------------ |
| limit |  -  |  -   |  No | No | Yes | 100 | Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |
| offset |  -  |  -   |  No | No | Yes | 0 | Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |


---

### Request Body

N/A

---

## Response Payloads

### Response Header


N/A
---

### Response Body

#### Payload 



| Parameter | Meaning | Sample | PII | Unique Identify | Mandatory | Default | Details |
| :----- | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :----- |
| name | name of the vehicle&#xD;&#xA;&#xD;&#xA;**lalal**&#xD;&#xA;&#xD;&#xA;***kakaka*** | Martin bike  |  No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |
| type | type of vehicle | bike  |  No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |
| country | country of the vehicle | Vietnam  |  No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |




#### Json sample
```
[
  [
    {
      "name": "Martin bike",
      "type": "bike",
      "country": "Vietnam"
    }
  ]
]
```



#### Json Schema
```
{
  "type": "array",
  "items": {
    "type": "array",
    "items": {
      "type": "object",
      "properties": {
        "name": {
          "type": "string",
          "title": "name",
          "examples": [
            "Martin bike"
          ],
          "description": "<p>name of the vehicle</p><p><strong>lalal</strong></p><p><strong><em>kakaka</em></strong></p>"
        },
        "type": {
          "type": "string",
          "title": "type",
          "examples": [
            "bike"
          ],
          "description": "<p>type of vehicle</p>"
        },
        "country": {
          "type": "string",
          "title": "country",
          "examples": [
            "Vietnam"
          ],
          "description": "<p>country of the vehicle</p>"
        }
      }
    },
    "title": ""
  }
}
```

