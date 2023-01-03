## Installing php:
------------------
* Manual steps:
---------------
[Refer Here](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-20-04#step-5-testing-php-processing-on-your-web-server) for the documentation for the installation steps of apache2 and php.
* Install 
     * apache2
     * php 
     * libapache2-mod-php 
     * php-mysql
* add `<?php
phpinfo();
?>`
to /var/www/your_domain/info.php 
* Then access the page with public-ip of the machine `http://<public-ip>/info.php` 
![Preview](Images/ansible1.png)
![Preview](Images/ansible2.png)