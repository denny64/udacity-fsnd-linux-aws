# udacity-linux-p5

* i. The IP address and SSH port so your server can be accessed by the reviewer.

  52.36.8.222 port 2200
  
* ii. The complete URL to your hosted web application.

  52.36.8.222
  
* iii. A summary of software you installed and configuration changes made.

  See iv.
  
* iv. A list of any third-party resources you made use of to complete this project.

Created a user called grader using ‘sudo adduser grader’
Made the grader user a sudoer by running sudo adduser grader sudo

Updated packages by running sudo apt-get update and sudo apt-get upgrade

Changed SSH port from 22 to 2200 in sshd_config file

Changed timezone to UTC using this command and package: sudo dpkg-reconfigure tzdata

Installed:
- apache2 
- libapache2-mod-wsgi
- postgresql
- git 
- git-man 
- liberror-perl
- python-pip

postgresql doesn’t allow remote connections by default
