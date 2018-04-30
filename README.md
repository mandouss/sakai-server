# Readme
## Sprint 1
In sprint 1, we set up the Sakai server and run it successfully.
The server is based on the MySQL database. 
 
 
### Set Environment variables
 Set up relevant Environment variables for Java and Apache Maven.
 
   
### Connect with MySQL database
Create a MySQL database to hold the data from Sakai, connect it with Tomcat tool.


### Compile
Compile the Sakai source code and start up the Sakai test server. 


Test Server\[link\](http://152.3.64.14:8080/portal/)

### How To set up your server

1. install apache2: sudo apt-get install apache2
2. install PH
3. change /etc/apache2/dir.conf: to specific which file to be executed first by Apache2 
4. put your .php or .html in /var/www/htm

** The instrcuction for the first 2 steps can be found at: https://www.howtoforge.com/tutorial/install-apache-with-php-and-mysql-on-ubuntu-16-04-lamp/

### Sprint 2
In sprint 2, we built a set-up shell script to set up sakai server automatically 

### Code Script Instructions

#### sakai_setup.sh

This script works to set up a test sakai server in your machine. It is referenced from https://github.com/sakaiproject/sakai/wiki/Quick-Start-from-Source
This script is more straightforward version of the online git guidance, as it collects all the bash commands.
Though ths script may not run all through by itself, the user can simply copy the lines from the script and run it in the bash command terminal. The only problem a user may encouter will be permission issue, which can be simply addressed by using "sudo".
The script has been tested.

#### getIP