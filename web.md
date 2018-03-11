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

### HTML5 input elements
* color* Provides a color picker
* date* Provides a date picker
* datetime* Provides a date/time picker
* month* Enables users to select a numeric month and year
* week* Enables users to select a numeric week and year
* time* Enables users to select a time of day
* number* Forces the input to be numeric
* Range Allows users to select a value within a range by using a slider bar
* tel* Formats entered data as a phone number
* url Formats entered data as a properly formatted URL
* Radio† Enables users to select a single value for a list of choices
* Checkbox† Enables users to select multiple values in a list of choices
* Password† Captures a password and glyphs the entered characters
* Button† Enables users to perform an action such as run script
* Reset† Resets all HTML elements within a form
* Submit† Posts the form data to a destination for further processing
1. *Not supported currently by Internet Explorer
2. †Not new in HTML5