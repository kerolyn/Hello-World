# How to test

## 
1. Signup
2. Signin by using curl command
    $ curl -b **my.cookie** -c **my.cookie** -X POST -d "name=**username**" -d "password=**password**" http://localhost:3000/signin
3. Call a method<br/>
3.1. GET
    $ curl -b **my.cookie** -c **my.cookie** -X GET http://localhost:3000/get
3.2. POST
    $ curl -b **my.cookie** -c **my.cookie** -X POST -H "Content-Type: application/json" -d "@**post_json_file**" http://localhost:3000/post
