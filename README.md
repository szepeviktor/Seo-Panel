Seo-Panel
=========

#### World's first seo control panel for multiple websites

This is the unoffical up-to-date mirror site of Seo Panel by [Geo Varghese](http://www.seopanel.in/)

```bash
find -not -path '*/.*' -type f \( -path "*.php" -o -path "*.js" -o -path "*.css" \) -exec dos2unix \{\} \;
find -not -path '*/.*' -type f \( -path "*.php" -o -path "*.js" -o -path "*.css" \) -exec sed -i 's/[ \t]*$//' \{\} \;
```

```bash
#git clone https://github.com/szepeviktor/Seo-Panel.git

#git pull
#git checkout master
#git checkout patches
#git checkout install
# update: SP_INSTALLED in config/sp-config.php

#USER="www-data"
#chown -R ${USER}:${USER} *
#chmod 400 config/sp-config.php
#chmod -R 750 tmp

# go to: http:// ... install/upgrade.php
#rm -rf install
```

- - -

## Seo Control Panel - Seo Panel Version 3.6.0

### Requirements

1. PHP, MYSQL, Web Server(e.g APACHE)
2. CURL enabled with PHP, Refer following link to install curl with php if it is not installed.
   http://php.net/manual/en/curl.setup.php


### Installation: Simple 5 minute installation

1. Download and Unzip the package
2. Upload all the files contained in this folder (retaining the directory structure) to a web accessible directory on your server or hosting account.
3. Change the permissions on "config/sp-config.php" to be writable by all (666 or -rw-rw-rw- within your FTP Client)
4. Change the permissions on the "tmp" directory to be writable by all (777 or -rwxrwxrwx within your FTP Client)
5. Using your web browser visit the location you placed Seo Panel with the addition of "install/index.php" or pointing directly to "install/", e.g. http://www.yourdomain.com/seopanel/install/
6. Follow the steps and fill out all the requested information.
7. Change the permissions on "config/sp-config.php" to be writable only by yourself (644 or -rw-r--r-- within your FTP Client)
8. Please use following login details to access Admin Interface.

    Admin Section:

        Username: spadmin
        Password: spadmin

    Note:
        Please change password of administrator by visiting 'Profile' link on right top of the seo panel to prevent from security threats.
        Remove "install" directory of seo panel

Installation Reference Link: http://www.seopanel.in/install/

If you have any issues while installation, Please use following resources to fix it or contact seo panel team.


### Online Seo Panel Resources:

1. Seo Panel Help Guide: http://help.seopanel.in/
1. Seo Panel Forum: http://forum.seopanel.in/
1. Seo Panel Support: http://www.seopanel.in/support/
1. Seo Panel Contact: http://www.seopanel.in/contact/


### The major features of Seo Panel

1. Automatic Directory Submission Tool
1. Keyword Position Checker
1. Site Auditor
1. Google and Alexa Rank Checker
1. Backlinks Checker
1. Search Engine Saturation Checker
1. Seo Panel Plugins
1. Meta Tag Generator


### Developed By [Geo Varghese](http://www.seopanel.in/)
