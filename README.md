# Udacity-Fullstack-Project5
Linux Server Configuration

###1. The IP address and SSH port so your server can be accessed by the reviewer.
  52.89.35.143
  2200

###2. The complete URL to your hosted web application.
  http://52.89.35.143/
  
###3. A summary of software you installed and configuration changes made.
  1. Installed apache
    1. Installed apache mod for wsgi
    2. Configured 000-default.conf to includ wsgi application alias to a wsgi file that will load the flask web app
  2. Installed postgresql
    1. Added "catalog" database and "catalog" user with permissions to that database
  3. Installed pip
    1. Used pip to install Flask
  4. Installed git
  5. Cloned project3 respository to /var/www/html/catalog
  6. Updated application code
    1. changed from sqlite to postgresql in both database_setup.py and application.py
    2. updated paths to the _secrets.json files to full paths
  7. Edited sshd_config to change ssh port to 2200
  8. Configured ufw and enabled it

###4. A list of any third-party resources you made use of to complete this project.
  1. Udacity forums and stackoverflow
