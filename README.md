# config-server
#### it has just one dependency: spring-cloud-config-server

### config:
// git path(it is my local git folder loaction)
* In bootstrap.properties
- spring.cloud.config.server.git.uri=/Users/ayush/Desktop/26_Jan/config-server

app-name.prop file 
* this key value will eb read by the client application as in client app ,app name is mention, ans this prop file is
with same name
message=This message is from server
