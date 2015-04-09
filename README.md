# hello-boot
This project is a copy of https://gitlab.com/jomoespe/dropwizard-sample but using Spring boot instead of dropwizard

#Usage
$ git clone https://github.com/jbbarquero/hello-boot.git

$ cd hello-boot/

$ mvn clean package

$ java -jar target/hello-boot-0.0.1-SNAPSHOT.jar --server.port=8000

$ curl localhost:8000/hello-world

$ curl localhost:8000/env
$ curl localhost:8000/health
$ curl localhost:8000/beans
$ curl localhost:8000/metrics
$ curl localhost:8000/trace
$ curl localhost:8000/dump

