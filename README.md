# microservices-demo

Demo application to go with my [Microservices Blog](https://spring.io/admin/blog/2181-microservices-with-spring) on the spring.io website.

![Demo System Schematic](https://github.com/mmiglier/microservices-demo/blob/master/mini-system.jpg)

## Usage

Compile and build docker images:
```
$ mvn clean package -P docker
```

Run:
```
$ cd docker/
$ docker-compose -up
```

See the result:
```
$ open http://$(docker-machine ip `docker-machine active`):3333
```

