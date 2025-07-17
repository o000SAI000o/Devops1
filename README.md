###Deployed various services each running on independent VMs,this scenario is for getting clear understanding about how each service runs on each VM and how they communicate using ports.

<img width="1326" height="696" alt="Screenshot 2025-07-12 180555" src="https://github.com/user-attachments/assets/5a988f83-c77b-4451-a622-1a1ffe0b5986" />


# Prerequisites
#
- JDK 17 or 21
- Maven 3.9
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


