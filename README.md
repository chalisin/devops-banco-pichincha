# devops-banco-pichincha
Banco Pichincha - DevOps Technical assessment Carlos Yánez

EndPoint URL

https://7z5zk931f7.execute-api.us-east-1.amazonaws.com/DevOps/DevOps

Headers

Content-Type: application/json
x-api-key: 2f5ae96c-b558-4c7b-a590-a501ae1c3f6c

Payload

{
  "message": "This is a test",
  "to": "Carlos Yanez",
  "from": "Estefania Barreno",
  "timeToLifeSec": 45
}

curl -X POST \
-H "x-api-key: 2f5ae96c-b558-4c7b-a590-a501ae1c3f6c" \
-H "Content-Type: application/json" \
-d '{ “message” : “This is a test”, “to”: “Carlos Yanez”, “from”: “Estefania Barreno”, “timeToLifeSec” : 45 }' \
