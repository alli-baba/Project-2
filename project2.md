# Project 2 Documentation




# Installing the nginx web server


`sudo apt install nginx`


![installing nginx](./Images/Installing%20the%20Nginx%20Web%20Server.png)



# Installing mysql



`sudo apt install mysql-server`


![Installing mysql](./Images/Installing%20mysql.png)


# Installing PHP



`sudo apt install php-fpm php-mysql`




![Installing PHP](./Images/Installing%20php.png)



# Configuring nginx to use php processor


`sudo ln -s /etc/nginx/sites-available/projectLEMP /etc/nginx/sites-enabled/`


![Configuring nginx to use php](./Images/configuring%20nginx%20to%20use%20php%20processor.png)



# Testing PHP with Nginx


`sudo nano /var/www/projectLEMP/info.php`


![Testing PHP with Nginx](./Images/Testing%20PHP%20with%20Nginx.png)


![Testing PHP with Nginx](./Images/Testing%20PHP%20with%20Nginx2.png)