# Twitter Process Application
The classical process application for Camunda BPM.

## Build it with maven

`mvn clean package` and copy `twitter.war` to the deployment folder

`mvn clean wildfly:deploy`to deploy directly to the running wildfly server.

`mvn clean package -Dmaven.test.skip=true` if you want to deploy very fast.
