# sajalka

## How to start application in docker-compose env (P.S. for linux only)?

```shell
$ docker-compose up
```
After some time you will see something like:
```shell
...
Creating sajalka_backend_1 ... done
Attaching to sajalka_backend_1
backend_1  | Running on http://0.0.0.0:8080
```
This means, that everything is fine, server has started, and you move on.
Now, we can make request to our server using curl or Postman or even browser.
Let's use curl for example, for that, open new terminal window and execute:
```shell
curl http://localhost:8080
```
As a result, you will see "Hello world" string as a response from server.