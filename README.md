# User Resources

DELETE /v1/vehicleManagement/

## Description

Get a user to access to the platform, default permission is client member

|                                       |                                                 |
| ------------------------------------- | ----------------------------------------------- |
| HTTP Method                           | Delete                                         |
| API                                   | Vehicle Management                                           |
| Api Version                           | 1.0.0.4                                         |
| Resource Version                      | 2                                               |
| Summary                               |  -                                       |
| Description Version                   |  -  |
| Base Path                             | /v1/vehicleManagement/                                     |
| Resource                              | Destroy vehicles                                      |
| Endpoint URL                          | https://api-dev.universalgalaxy.co/v1/vehicleManagement/              |
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


N/A
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
| id | Identification&#xA0;Data of vehicle | 81X1-03192  |  No | No | No |  -  | Data Type : string<br> Min. length :  - <br> Max. length : No<br> Regex :  - <br>  |




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

