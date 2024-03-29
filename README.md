# helidon-mp-jpa [![Build Status](https://travis-ci.org/daggerok/helidon-mp-jpa.svg?branch=master)](https://travis-ci.org/daggerok/helidon-mp-jpa)
Helidon MicroProfile JPA problem solving!

```bash
./mvnw
java -jar target/*-all.jar

http :8080/bank-account username=username balance=123.45
http :8080/bank-account
http :8080
http :8080/not-found ololo=trololo
http :8080 hello=world
http :8080/openapi
http :8080/openapi Accept:application/json
http :8080/health
http :8080/metrics
http :8080/metrics Accept:application/json
http :8080/static/microprofile-quickstart-integration-tests.http
```

links:

* [helidon.io](https://helidon.io)
* [FAQ](https://github.com/oracle/helidon/wiki/FAQ)
* [Support next MicroProfile APIs](https://github.com/oracle/helidon/wiki/Supported-APIs)
* [static content](https://github.com/oracle/helidon/tree/master/examples/microprofile/mp1_1-static-content)
* [jul -> log4j2](http://logging.apache.org/log4j/2.x/faq.html#which_jars)
* [Helidon WebServer Introduction](https://helidon.io/docs/latest/#/webserver/01_introduction)
* [Helidon WebServer Configuration](https://helidon.io/docs/latest/#/webserver/02_configuration)
* [Server configurations](https://helidon.io/docs/latest/apidocs/index.html?io/helidon/webserver/ServerConfiguration.html)
* [Routing](https://helidon.io/docs/latest/#/webserver/03_routing)
* [JAX-RS Support](https://helidon.io/docs/latest/#/webserver/07_jersey-support)
* [JSON-P](https://helidon.io/docs/latest/#/webserver/08_json-support)
* [Jackson / JSON-P Jersey JAX-RS problem-solving](web-server-jersey-jsonp)
* [JSON-B](https://helidon.io/docs/latest/#/webserver/09_jsonb-support)
* [Jackson support](https://helidon.io/docs/latest/#/webserver/10_jackson-support)
* [Hierarchical features](https://helidon.io/docs/latest/#/config/03_hierarchical-features)
* [fold the universe](https://dzone.com/articles/folding-the-universe-part-iii-java-8-list-and-stre)
* [Configs](https://helidon.io/docs/latest/#/webserver/02_configuration)
* [Advanced Config Sources](https://helidon.io/docs/latest/#/config/06_advanced-configuration)
* [Useful GitHub helidon-mp-jpa repository](https://github.com/ljnelson/helidon-mp-jpa)
