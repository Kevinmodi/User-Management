Request Method:POST

Request URL: http://localhost:8080/signup

RequestHeader:
content-type: application/json

Request Body:
{"firstName":"Kevin","lastName":"Modi","mobile":9662244182,"gender":"male","userName":"kevinmodi"}


Response(Success):
{"success":true}

Response HTTP Status Code:
200


Failure Response:
{"success":false,"reason":"Invalid input"}

Response HTTP Status Code:
400

Failure Response:
{"success":false,"reason":"Internal Server Error"}

Response HTTP Status Code:
500
