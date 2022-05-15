### 起動方法
- ```$ cd backend```
- ```$ docker compose up -d```
- ```$ docker compose exec db bash```
- ```$ mysql -u root -p```
- ```$ password: root_password```
- ```mysql> CREATE DATABASE test_database;```
- ```mysql> exit```
- ```$ docker compose exec go sh```
- ```/go/src # go run cmd/main.go -option=migrate```
- To exit a go container, ```Control + c```
- ```cd ../frontend```
- ```npm install```
- ```npm run start```