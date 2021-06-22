## Curl

### curl can be used to access rest api

> It supports fetching/transferring data to server using different protocols e.g. HTTP/HTTPS/FTP etc.

* GET url

`curl <url>`

`curl "https://api.openweathermap.org/data/2.5/weather?q=bengaluru&appid=acd1c9c0df79d1e3b55201c4f347605a&units=metric"`

* GET url with headers

`curl -i <url>`

* save data in file

`curl -o <filepath> <url>`

* POST data
> Use -H for headers

`curl -i -X POST -H "Accept: application/json" https://reqres.in/api/users -d "name=Mavixk&job=coder"
`
