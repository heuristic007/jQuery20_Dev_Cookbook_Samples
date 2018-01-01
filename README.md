# jQuery20_Dev_Cookbook_Samples
This is an exercise for samples from jQuery 2.0 Development Cookbook by Leon Revill
The development environment is on Windows 10 with Apache 2.4, PHP 7.2, jQuery, HTML 
and MySQL.

In this practice, following environments are set up on Windows 10 -
1. Apache24 is installed in c:\Applications\Apache24
2. PHP 7.2 is installed in C:\Applications\php7
3. php files are placed in C:\Applications\Apache24\htdocs
4. httpd.conf is modified for environment needed
5. Apache 2.4 is downloaded from https://www.apachelounge.com/download/
6. To connect to MySQL, PHP config file php.ini has to make some changes -
   a. add or uncomment this line - extension=php_mysqli
   b. uncomment ;extension_dir = "ext" to extension_dir = "ext"
      ext is the folder contains php_mysqli.dll
   php7 is used in this practice. Earlier php version might have different setup.

