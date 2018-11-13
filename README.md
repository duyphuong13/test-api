# User Resources

Delete /v2/vehicleManagement/

## Description

Get a user to access to the platform, default permission is client member

|                                       |                                                 |
| ------------------------------------- | ----------------------------------------------- |
| HTTP Method                           | Delete                                         |
| API                                   | Vehicle Management                                           |
| Api Version                           | 2.0.0.10                                         |
| Resource Version                      | 7                                               |
| Summary                               | N/A                                      |
| Description Version                   | N/A |
| Base Path                             | /v2/vehicleManagement/                                     |
| Resource                              | Destroy vehicles                                      |
| Endpoint URL                          | https://api-dev.universalgalaxy.co/v2/vehicleManagement/              |
| Service Status                        | N/A                                         |
| Legislative / Regulatory / Compliance | N/A                                             |
| Firewalls Details                     | N/A                                             |
| Security Certificate Details          | N/A                                             |
| Vendor or Partner Considerations      | N/A                                            |

## Request Payloads

### Request Header



| Header | Meaning | Sample | PII | Unique Identify | Mandatory | Default | Details |
| ------------- | :-----: | -----: | --- | --------------- | --------- | ------- | ------------------ |
| sssss | - |  -   |  No | No | Yes |  -  | Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |


---

### Query Params



| Parameter | Meaning | Sample | PII | Unique Identify | Mandatory | Default | Details |
| ------------- | :-----: | -----: | --- | --------------- | --------- | ------- | ------------------ |
| xxxx | - |  -   |  No | No | Yes |  -  | Data Type : integer<br> Mininum :  - <br> Exclusive Minimum : No<br> Maximum :  - <br> Exclusive Maximum : No<br> Multiple Of :  - <br>  |


---

### Request Body

N/A

---

## Response Payloads

### Response Header



| Header | Meaning | Sample | PII | Unique Identify | Mandatory | Default | Details |
| ------------- | :-----: | -----: | --- | --------------- | --------- | ------- | ------------------ |
| xxxx | - |  -   |  No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |


---

### Response Body

#### Payload 



| Parameter | Meaning | Sample | PII | Unique Identify | Mandatory | Default | Details |
| :----- | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :----- |
| id | - | 81X1-03192  |  No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |




#### Json sample
```
{
  "id": "81X1-03192"
}
```



#### Json Schema
```
{
  "type": "object",
  "properties": {
    "id": {
      "type": "string",
      "title": "id",
      "examples": [
        "81X1-03192"
      ],
      "description": "<p>Identification&nbsp;Data of vehicle</p>"
    }
  }
}
```

