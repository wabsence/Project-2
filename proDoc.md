# PROJECT DOCUMENTATION

## Step 1: NGINX INSTALLATION

#### Command: sudo apt update (Packages update in Package Manager)
#### Output:

![packages Updated](images/update.png "packages update process")

#### Command: sudo apt install nginx (ngnix Installation)
#### Output:

![nginx Installation](images/nginx.png "nginx installation process")

#### Command: sudo systemctl status apache2 (Apache Status Confirmation)
#### Output:

![Nginx Installation](images/nginx2.png "apache in running state")

#### Command:  curl http://127.0.0.1:80 (Localhost access via IP)
#### Output:

![Accessing Server](images/nginx3.png "accessing server via IP address")

#### Command:  http://54.237.100.243/(Accessing IP address via browser)
#### Output:

![Accessingg Server](images/nginxServer.png "accessing apache server")

## Step 2: MYSQL INSTALLATION

#### Command: sudo apt install mysql-server (Mysql Installation)
#### Output:

![MYSQL_1](images/mysql.png "MYSQL Installation")

#### Commands: $ sudo mysql and ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'PassWord.1'; (connect to mysql and change password)
#### Output:

![MYSQL_2](images/mysql2.png "MYSQL")

#### Command: $ sudo mysql_secure_installation (Mysql Installation)
#### Output:

![MYSQL_3](images/mysql3.png "MYSQL")

#### Command: $ sudo mysql -p (Login to mysql)
#### Output:

![MYSQL_3](images/mysql4.png "MYSQL")

## Step 3: PHP INSTALLATION

#### Command: sudo apt install php-fpm php-mysql
#### Output:

![PHP](images/php.png "PHP Installation")
