# HTTP Requests
* get
* post
```
GET http://weather.example.org/oaxaca HTTP/1.1   // хочемо отримати це посилання, версія HTTP протоколу
HOST: weather.example.org   // сервер
Accept: application/xhtml+xml   // шо клієнт очікує
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
### поширені HTTP Status Codes
* 200 - OK
* 404 - ресурс не знайдено
* 500 - помилка сервера
### Status Code Ranges
* 100s - інформативні
* 200s - успішні
* 300s - перенаправлення(шось перемістилось)
* 400s - помилки клієнта
* 500s - помилки сервера