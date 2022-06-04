# Flow Of Execution 
1. Login to AWS account. 
2. Create login key. 
3. Create Security Groups for Jenkins, Nexus, Sonarquabe. 
4. Create Ec2 instances with userdate for Jenkins, Sonarqube, Nexus.
5. Jenkins Post installation. 
6. Nexus Repository setup. 
7. Sonarqube post installation. 
8. Jenkins Steps - Build Job, Setup Slack Notification, Checkstyle code analysis job,
   Setup Sonar integration, Sonar code analysis job, Arfifact upload job. 
9. Connect All jobs together with BuildPipeline. 
10. Set Automatic build trigger. 
11. Test with intellij. 
















####
### Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

### Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
### Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


