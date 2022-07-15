# Docker swarm with golang & mysql example

#### image was pushed on docker hub 
~~~
version 1.2 - 1.3 not use db
version 1.4 connect with mysql
goapi write by gorilla / gorm
use dep and go module
docker stack deploy -c=docker-compose.yaml full_stack
make sure have path volumn in whole node

connect from go to mysql with service name
gorm.Open("mysql","root:admin@tcp(mysqldb:3306)/golangdemo?charset=utf8&parseTime=True&loc=Local")

~~~

# Use share volume with third party
