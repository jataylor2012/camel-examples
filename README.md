camel-examples
==============

This is an example project that shows how to configure a camel route using only the Spring DSL.

There is no source code. It is just a webapp that loads a spring context & a camel context.

There are two routes, directory -> activemq & activemq -> directory.

This project can be run using mvn jetty:run or the war can be dropped in a jee container i.e tomcat/webapps
