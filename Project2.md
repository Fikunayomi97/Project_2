# Project 2 documentation


`sudo apt update`

![update](./Images/apt_update.PNG)

`sudo apt install nginx`

![install_nginx](./Images/Install_nginx.PNG)

`sudo systemctl status nginx`

![nginx-status](./Images/nginx_status.PNG)

`curl http://localhost:80`

![nginx_on_terminal](./Images/nginx_on_terminal.PNG)

![nginx_welcome_page](./Images/nginx_welcome_page.PNG)

`sudo apt install mysql-server`

![installing_mysql](./Images/Installing_mysql.PNG)

## Installing PHP and Interpreter

`sudo apt install php-fpm php-mysql`

![installing_php](./Images/Installing_php.PNG)

### Activating Configurations

![activating_configurations](./Images/Activating_configurations.PNG)

`sudo echo 'Hello LEMP from hostname' $(curl -s http://169.254.169.254/latest/meta-data/public-hostname) 'with public IP' $(curl -s http://169.254.169.254/latest/meta-data/public-ipv4) > /var/www/projectLEMP/index.html`

![landing_page_for_html](./Images/result.PNG)

`sudo nano /var/www/projectLEMP/info.php`

![php_info_page](./Images/php_info.PNG)

### Creating database and user

![creating_database_and_user](./Images/creating-user-and-database.PNG)

`INSERT INTO example_database.todo_list (content) VALUES ("My first important item"),`

![to_do_list](./Images/creating_to-do-list_on_mysql.PNG)

![to_do_list_on_browser](./Images/To-do-browser.PNG)
