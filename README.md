# DevEnv-Docker-Python3-MySQL
Development Environment using Docker implementing python3 and MySQL used for developing python applications.


## Quick Start Guide

To get this docker container up and running simply build and start using the following commands 
from within the `docker` directory.

`> cd docker`

`> ./build.sh`

`> ./start.sh`

You can access the application by running the command below.

`> connect-app.sh`

Once finished call the stop command to bring down docker container and application.

`> ./stop.sh`


The following sections provide further details on the docker methods used within each script.


# Database

MySQL and PHPMyAdmin

#### PhpMyAdmin

You can access the database using phpmyadmin within this project.
Navigate to this url `http://127.0.0.1:8181/index.php`

Enter the following details

- Server: webapp-mysql
- Username: webapp_user
- Password: password


## Acknowledgements 

This project is based on 
<a href="https://github.com/aalshukri/DevEnv-Docker-Python3">https://github.com/aalshukri/DevEnv-Docker-Python3</a>.

Main differences between DevEnv-Docker-Python3 and DevEnv-Docker-Python3-MySQL
is I have added a MySQL database for usage with the python application.


