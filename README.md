# spring-data-mongodb

```
2019-02-02 20:54:13.755  INFO 93481 --- [           main] o.s.j.e.a.AnnotationMBeanExporter        : Registering beans for JMX exposure on startup
2019-02-02 20:54:13.764  INFO 93481 --- [           main] hello.Application                        : Started Application in 1.115 seconds (JVM running for 1.616)
2019-02-02 20:54:13.782  INFO 93481 --- [           main] org.mongodb.driver.connection            : Opened connection [connectionId{localValue:2, serverValue:2}] to localhost:27017
Customers found with findAll():
-------------------------------
Customer[id=5c5649c509097d6d2906a0d0, firstName='Alice', lastName='Smith']
Customer[id=5c5649c509097d6d2906a0d1, firstName='Bob', lastName='Smith']

Customer found with findByFirstName('Alice'):
--------------------------------
Customer[id=5c5649c509097d6d2906a0d0, firstName='Alice', lastName='Smith']
Customers found with findByLastName('Smith'):
--------------------------------
Customer[id=5c5649c509097d6d2906a0d0, firstName='Alice', lastName='Smith']
Customer[id=5c5649c509097d6d2906a0d1, firstName='Bob', lastName='Smith']
2019-02-02 20:54:13.889  INFO 93481 --- [       Thread-2] s.c.a.AnnotationConfigApplicationContext : Closing org.springframework.context.annotation.AnnotationConfigApplicationContext@214b199c: startup date [Sat Feb 02 20:54:12 EST 2019]; root of context hierarchy
2019-02-02 20:54:13.891  INFO 93481 --- [       Thread-2] o.s.j.e.a.AnnotationMBeanExporter        : Unregistering JMX-exposed beans on shutdown
```