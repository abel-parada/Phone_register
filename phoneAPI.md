# Phone API

## data

Data will be in a json file

### phones.json

```json
[
  {
    "firstname": "Leila",
    "lastname": "Hökki",
    "phones": [
      { "type": "home", "number": "12345678" },
      { "type": "work", "number": "19876543" },
      { "type": "work", "number": "34567895" }
    ]
  },
  {
    "firstname": "Abel",
    "lastname": "Parada",
    "phones": [
      { "type": "home", "number": "56779376" },
      { "type": "work", "number": "41254657" },
      { "type": "mobile", "number": "76543245" }
    ]
  }
]
```

## Class PhoneRegister

## **constructor(data)**

Phones json array is passed as a parameter `data`. If the parameter is missing, throws an exception `'phone data missing'`.
