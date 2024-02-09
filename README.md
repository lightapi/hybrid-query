# Light Hybrid 4J Query Server

This is a light-hybrid-4j server for query side services. All readonly light-hybrid-4j
services should be deployed on this server.

## Start server

from root folder

```text
 mvn clean install -Prelease

 java -jar -Dlight-4j-config-dir=config/local target/hybrid-query.jar

```
