# IMPLEMENT A CLIENT SERVER ARCHITECTURE USING MYSQL DATABASE MANAGEMENT SYSTEM (DBMS)

## To Implement a Client Server Architecture using MySQL Database Management System (DBMS)

### To demonstrate a basic client-server using MySQL Relational Database Management System (RDBMS):

### To create and configure two Linux-based virtual servers (EC2 instances in AWS)

```
Server A name - `mysql server`
Server B name - `mysql client`
```
![server name](./images/server-name.png)

### Installing  MySQL Server software on mysql server Linux

`sudo apt install mysql-server`

![installing mysql server](./images/install-mysqlserver.png)

![installing mysql server](./images/install-mysqlserver2.png)

### Installing  MySQL Server software on mysql server Linux

`sudo apt-get install mysql-client`

![installing mysql client](./images/install-mysqlclient.png)

### By default, both EC2 virtual servers are located in the same local virtual network, so they can communicate to each other using local IP addresses. 

### Using mysql server's local IP address to connect from mysql client, and vice versa.

![communicating with mysql client from mysql server](./images/communicate-1.png)

![communicating with mysql server from mysql client](./images/communicate-2.png)