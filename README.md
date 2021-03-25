# Naming Server

![Desing Overview](https://raw.githubusercontent.com/khabib97/spring-cloud-microservice-interaction/master/overview.png)

This is a submodule. For better underesting visit main project repo:

https://github.com/khabib97/spring-cloud-microservice-interaction

Nameing server is created using netflix-eureka-server. Currency Exchange Service and Currency Conversion Service register them to Naming Server as eureka-client. 

Using `feign client` currency conversion service calls currency exchange service. 

It also perform client side load balancing

- Clone naming-server
- Import as maven porject
- And run as java application

To view register services:
```
http://localhost:8761/
```
