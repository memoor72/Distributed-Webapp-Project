# Distributed-Webapp-Project
First deployed compute instances -2 webservers and 1 database server on the google platform
Then Installed the required Python dependencies for the db server after which the applications -MYSQL,PyMySQL were installed
Updated MySQL configuration file with bind-address 0.0.0.0 and port number 3306
Then copied the /.my.cnf file to the target server and updated with the root login credentials
Then disabled auth_socket plugin for root user.
Created  Application Database and DB User,then Granted all privileges on employee_db to db_user
Then Installed the required Python dependencies for the Flask application then installed flask application 
Downloaded the source code to webserver using git and then started web application
Then setup networking by adding a firewall rule which Allows HTTP traffic on port 80 between the loadbalancer and the compute instances
The created the load balancer and added the members to it
Finally created an email notification detailing the sucessfully completion of the ansible Job
