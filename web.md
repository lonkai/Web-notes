# HTTP Requests
* get
* post
```
GET http://weather.example.org/oaxaca HTTP/1.1   // get this link and version of HTTP protocol
HOST: weather.example.org   // server
Accept: application/xhtml+xml   //client is expected to get back
```
### Server response
```
HTTP/1.1 200 OK
Content-Length: 45178
Content-Type: application/xhtml+xml; charset=utf-8

<!DOCTYPE html PUBLIC "...>
<html xmlns="http:/www...
 <head>
  <title>5 day forecast...
```
### Common HTTP Status Codes
* 200 - OK
* 404 - Resource not found
* 500 - Server Error
### Status Code Ranges
* 100s - інформативні
* 200s - успішні
* 300s - перенаправлення(шось перемістилось)
* 400s - помилки клієнта
* 500s - помилки сервера