#  Drupal.Farm

## The Plan

This is a private repo.  

Keep secrets in _________.  

This will be pushed/pulled to /var/www/drupal.farm  

Phase I: master theming and twig to make a couple of non functional static pages  

Phase II: with WeaverRyan and drupalize.me make controllers, dB stuff.  

The dream: by July: this and Pikl.Us-symfony  


## Tuesday installing to Digital Overground

### PHP

you will get error messages during installation if any required PHP extensions are missing, and should be able to install them and continue.   

### Apache

The Apache VirtualHost configuration must contain the directive AllowOverride All to allow the .htaccess file to be used. 

This is anti-pattern for performance.  See more at the "Apache HTTP Server Tutorial: .htaccess files".  The skinny: anything that is in htaccess is faster when put up in the real config.  htaccess is a neccessary evil for making the CMS convenient to edit. Also: you are giving the CMS controller access to server control, which is not a best security practice.



### SQL

PostGres, SQLite, MariaDB, and MySQL all are compatible actually   





