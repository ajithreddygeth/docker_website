Build docker image:
```
$ docker build -t my_website:0.1 .
```
Docker run
```
$ docker run --rm -p 8080:8080 my_website:0.1
```