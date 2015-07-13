# How to test

1. Signup
2. Signin by using curl command<br/>
```sh
$ curl -b cookie_file -c cookie_file -X POST -d "name=user_name" -d "password=pass_word" http://localhost:3000/signin
```
## Call a method
1. GET
```sh
$ curl -b cookie_file -c cookie_file -X GET http://localhost:3000/foo
```
2. POST
```sh
$ curl -b cookie_file -c cookie_file -X POST -H "Content-Type: application/json" -d "@post_json_file" http://localhost:3000/bar
```
