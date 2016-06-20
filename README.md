# api-classical
API to provide classical composers and works information

# Note
```HTTP
GET https://api-classical.0x0.tw/composers HTTP/1.1

200 OK
[{"composer_id": "3sdf2","name": "composer_a"},{"composer_id": "23efkd","name": "composer_a", ...}]
```

```HTTP
GET https://api-classical.0x0.tw/composers/3sdf2/works HTTP/1.1

200 OK
{
  "composer_id": "3sdf2",
  "works": [
  
  ]
}

```

