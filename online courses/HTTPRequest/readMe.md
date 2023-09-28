# HTTP Request Documentation

```cmd
curl -X GET <link code> -i

```

Explanation: 
`curl` is a command to use the cURL program in Terminal or CMD.
`-X GET` sets the HTTP method/verb we are using. GET means we want to retrieve data.
`https://coffee-api.dicoding.dev/coffees` is the target request address.
`-i` provides detailed information about the response received (HTTP response headers).


```cmd
curl -X POST -H "Content-Type: application/json" -d "{\"name\": \"contentName\"}" <link name>  -i

```
