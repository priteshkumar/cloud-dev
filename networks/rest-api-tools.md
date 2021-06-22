## Curl

### curl can be used to access rest api

> It supports fetching/transferring data to server using different protocols e.g. HTTP/HTTPS/FTP etc.

* GET url

`curl <url>`

* GET url with headers

`curl -i <url>`

* save data in file

`curl -o <filepath> <url>`

* POST data
> Use -H for headers

`curl -i -X POST -H "Accept: application/json" https://reqres.in/api/users -d "name=Mavixk&job=coder"
`
