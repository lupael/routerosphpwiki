Auto Installer
----
1. Unzip the contents of the zip file to a folder on your computer.
2. Upload the Entire phpmixbill folder to your website / server
3. Next you can rename the folder to whatever you like (billing, finance, manage etc..)
4. Now visit the uploaded location using your web browser to run the installer process.
5. Follow the instructions on screen to install PHPMixBill 
6. For security, Delete the install directory inside **system** folder.
7. If you see blank page after installation, it might be your compiled folder permission is not writable. Please make permission 755 compiled directory inside **ui** folder to store the generated contents from theme.

if you get error after submit database configuration, create chmod 777 folder **system**, retry instalation, after finish, chmod 755 folder **system**

Manual Install
----
To install manually, follow this steps-

1. Unzip the contents of the zip file to a folder on your computer.
2. Upload the Entire phpmixbill folder to your website / server
3. Next you can rename the folder to whatever you like (billing, finance, manage etc..)
4. Sample config file is available here- system/config.sample.php, Rename it to config.php & put it in same location (/system/config.php) Open config file using a text editor & Put the database info and url.
5. Import database. Database file is located here- system/install/phpmixbill.sql
6. For security, Delete the install directory inside system folder.

CHMOD
----
Make writeable file html inside **pages** except index.html

    chmod 664 pages/*.html
    chmod 644 pages/index.html

