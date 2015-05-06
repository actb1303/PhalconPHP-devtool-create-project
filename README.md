Phalcon PHP - DevTools creates project in 30 seconds
====================

Use phalcon devtool to create a simple project in 30 seconds

Thanks.

Get Started
-----------

### Configuration

Check your database configuration and website's base URI.

    app/config/config.php

Then you'll need to create the database and Product table:

    mysql:
    create database test;
    use test;
    CREATE TABLE IF NOT EXISTS product (
        id     INT UNSIGNED NOT NULL auto_increment,
        name      text NOT NULL,
        price      text NOT NULL,
        description text NOT NULL,
        PRIMARY KEY (id)
    ) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
    
### Devtools commands
In this demo, we used some commands as below:
    cd /var/www/html
    sudo phalcon create-project demo
    cd demo/
    sudo phalcon scaffold product
    
    cd /var/www/html
    sudo phalcon create-project demo
    cd demo/
    sudo phalcon scaffold product
### RUN check demo project

    /demo/product/search
    /demo/product/new
    /demo/product/new
    /demo/product/edit/1
    