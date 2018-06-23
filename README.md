# project6

### About
  This Project is about configuring the Linux-Server.
  
  The list of software installed are:

1.Python

2.Postgresql

3.Flask environment

4.Apache2

### Server Details

Server IP Address 13.232.99.160

Hosted site Url [http://13.232.99.160.xip.io/](http://13.232.99.160.xip.io/)

### Steps to connect as grader:

  save private key provided in your local machine and run the following command
  ```
  ssh -i path/to/privatekey -p 2200 grader@13.232.99.160
    
  ```
  
### Id_rsa key
```
-----BEGIN RSA PRIVATE KEY-----
MIIEpAIBAAKCAQEA0nuw1qCJKtoqLjhYm4nm4e+KbGQkA3WQTypf4u364DXvpD7l
y2Nk6dsdiKXfrpWWM5TpLSaYVp5tk07iZHHtQQQXX12614frcy+H3b+qXdnerZBh
OAHuqIoortLk/ux0md5EZyn6j0Jig9aRSTDajjdjAZ0bFsq4jan2MI9YFjwAn3k8
LbujIDqyiRwUVIaqki3CZwljCSf9bA1cAf6kj/o5OypDQrJJXyzysY2kVWzbhL0s
6GLE5v1NIIJRTfzm0LXdIszBK7g0NlZF1+EPXl/vWv9K++ZRm6DJvh6Lxv/WcQCk
KSt460aOGAZRardHRn/xwnN1B6dMRvOSfoLQtwIDAQABAoIBAHL0jQtbWC7oQhtG
ONaSBWAmJJK4Spb9EVi7Su00jk0ACCbLF1Pyr/2s5z9nYHgISKVZUdSP/KlqE2xd
q/Wx5yMYKe+y0EXAfQ5GykyIznI9eImQjhg5re+srTV2Bw1XdQNISlGRsr+lQQrC
GE1B+kur4k3SUSYsh4kPZ170Gubg1iIkfwjoHQJhp/XKXMje4WWi1XFkO6jbKVjE
eZ6I/Fu1u9/bTyTyIFZBMv2ewkkr3gRF1YM52TYZQuo13s9cs3mC2czh6MJGUP8S
F1eRBFoJGX2A1gnp0rzMrdyMD8BOS1IL8OskFxXfSCIFj48Ndvg++XOgR0/Vl5Xv
RPBERBkCgYEA+r/tb+LgA1rGX/6X3gYs7hcrWsEVZpICpCxfZz/AzXTjZyOIMqU4
UPqJ1yI8QAduZGacA0t9+gI1yvAaLuDF5AiKYxSu/hNi2oHDWdDZVkhtYyxNc+OB
87GhWOUpFOPEqtGOkcVApied8uLWBFiCqppcXFHHOFEVIu6UWtlwP3MCgYEA1uPt
CAoQkp1j07FmnoUGTbIhSaScW0vY9+vvbMXxLRtCmGfCHTOFcpYa9oxdqJg/V4Z3
qcmkhs4EfQk+H0GrHUIKpybi86ohlnX6Fwz08RoHNOY7qPGVwz/oUe8Uzam/j5vR
SjEDxpznuYf04EnSNhyFwew482FnHciOSYHcUK0CgYEAnYUIUatCcpkJ2bAEE1Pp
0b/4WlDFcuPyiNPfMutX4Tm2yUoG+1nTYPuir+Uv2EFS1funsmIwR2gwBsaCjERj
zHaZCNkrfS0MgpvV7oxGm+9v2EcyeMTJFB/YbhG3lwnmuDBg0a4KiNaGYNii/aPk
oevKbaxp7DTzhDhANjo2S4UCgYBXk5plXVy1s+kcPD9bOVGBVqhUT/7dAkNRftkb
1mvc+zAf1qF4ryeitGQWuMvuyuV9sTKRgrlHqyyPHLYxnNy01tZqmuGBdoOrwzcC
L+ifXgEz4OTNjG+BnEj9I1eyHY0RZOpdty4Xwph5t1voEI3YObWVe8UWA0s4CyVZ
9c+pHQKBgQCmJdnCmfHHQe1JFt6m1SPnVTe2J1eX9QHQCyi9P4uwX8iwfF8ykG0y
aDRGq8BhgaDkmLCRvao2B6XgDRHH39F8upUloA2MIhO29+t9rOvVNlnpAGvOFE/f
j7gh/sAnbe76u8eqfIJcZGT6STMAY8sI8T3SoU+KnP7jGr0+x5Df6g==
-----END RSA PRIVATE KEY-----
```
### passpharse password
'''
passpharse password is empty(you can directly press enter).

'''
### id_rsa.pub key
```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDSe7DWoIkq2iouOFibiebh74psZCQDdZBPKl/i7frgNe+kPuXLY2Tp2x2Ipd+ulZYzlOktJphWnm2TTuJkce1BBBdfXbrXh+tzL4fdv6pd2d6tkGE4Ae6oiiiu0uT+7HSZ3kRnKfqPQmKD1pFJMNqON2MBnRsWyriNqfYwj1gWPACfeTwtu6MgOrKJHBRUhqqSLcJnCWMJJ/1sDVwB/qSP+jk7KkNCsklfLPKxjaRVbNuEvSzoYsTm/U0gglFN/ObQtd0izMEruDQ2VkXX4Q9eX+9a/0r75lGboMm+HovG/9ZxAKQpK3jrRo4YBlFqt0dGf/HCc3UHp0xG85J+gtC3 rahul@DESKTOP-O899F43
```
### grader password
```
acerahul
```
### Configuring Linux Server

#### Updating all packages
```
sudo apt-get update
sudo apt-get upgrade
```

#### Creating grader User:
  ```
  sudo adduser grader
  ```
  This will add new user
  ```
  sudo nano /etc/sudoers
  ```
  Below the Root user append the following line
  ```
  grader  ALL=(ALL:ALL) ALL
  ```
  This will grant sudo permission to grader
  #### Creating a ssh key pair for grader
   On your local machine in terminal/command prompt type
   ```
   ssh-keygen
   ```
   Which will generate the public and private ssh keys which is saved to .ssh folder
   
   Then in your virtual machine change to newly created user
   ```
   su - grader
   ```
   Create a new directory .ssh and new file authorized_keys in that directory
   ```
   mkdir .ssh
   sudo nano .ssh/authorized_keys
   ```
   Copy the public key with .pub extension to authorized_keys and save the file
   ```
   chmod 700 .ssh
   chmod 644 .ssh/authorized_keys
   ```
   - 700 will give read write and execute permission to user.
   - 644 prevent other user from writting in to file.
   Then restart ssh server
   ```
   service ssh restart
   ```
   
   Log in to grader with private key generated 
   ```
   ssh -i .ssh/id_rsa grader@ipaddress 
   ```
  #### Changing the ssh port to 2200
   ```
   sudo nano /etc/ssh/sshd_config
   ```
    
   Restart the ssh server
   
   ```
   service ssh restart
   ```
   
   >Note: Before Logging using ssh add custom TCP port 2200 under lightsaail firewall in networking tab in lightsail instance console  
   
   Now Login using command like this
   ```
   ssh -i .ssh/id_rsa -p 2200 grader@youripaddress
   ```
   
  #### Disabling ssh login as root
  `sudo nano /etc/ssh/sshd_config`
  
  make change `PermitRootLogin no`
  
  #### Configurating  Ufw firewall
  ```
  sudo ufw status
  sudo ufw allow 2200/tcp
  sudo ufw allow 80/tcp
  sudo ufw allow 123/udp
  sudo ufw enable
  ```
  This will allow all required ports and enables the ufw
  ```
  sudo ufw status
  ```
  It will display all allowed ports
  
  #### Changing time Zone
  `sudo dpkg-reconfigure tzdata`
  
  select none from list and then select utc.
  
  #### Installing Apache2 
  In terminal 
  
  ```sudo apt-get install apache2```
  
  Now mod_wsgi
  
  ```sudo apt-get install python-setuptools libapache2-mod-wsgi```
  
  Enable mod_wsgi
  
  ```sudo a2enmod wsgi ```
  ##### Setting up your flask application to work with apache2
   Creating a flask app
   
   In /var/www directory create a new folder
   `sudo mkdir FlaskApp`
   
   Install git 
   
   `sudo apt-get install git`
   
   move to the FlaskApp `cd FlaskApp`
   
   In that direcory clone your github repository
   
   `sudo git clone https://github.com/username/catalog.git`
   
   Rename your repository to FlaskApp
   
   Then rename your project file to `__init__.py`
   
   >Error : While accesssing the client_secrets.json file 
   ```
   PROJECT_ROOT = os.path.realpath(os.path.dirname(__file__))
   json_url = os.path.join(PROJECT_ROOT, 'client_secrets.json')
   CLIENT_ID = json.load(open(json_url))['web']['client_id']
   ```
   Use json_url instead client_secrets.json in script
   
  ##### Install and configuring postgresql for project
   Install Postgres `sudo apt-get install postgresql`
   
   login to postgres `sudo su - postgres`
   
   postgres shell `psql`
   
   create user `CREATE USER catalog WITH PASSWORD 'password';`
   
   permit user to createdb `ALTER USER catalog CREATEDB;`
   
   Create a db name  catalog with user catalog `CREATE DATABASE catalog WITH OWNER catalog;`
   
   connect to db `\c catalog`
   
   revoke all permission to public `REVOKE ALL ON SCHEMA public FROM public;`
   
   Give schema permission to user catalog `GRANT ALL ON SCHEMA public TO catalog;`
   
   exit from db and postgres `\q and exit`
   
   Change the database connection in both db_setup.py and `__init__.py` as `engine =       create_engine('postgresql://catalog:password@localhost/catalog')`
   
   Now you are ready with your applicatiom
  #### Configure and Enable a New Virtual Host
   `sudo nano /etc/apache2/sites-available/FlaskApp.conf`
   
   In this add the following code
   ```
   <VirtualHost *:80>
		ServerName mywebsite.com
		ServerAdmin admin@mywebsite.com
		WSGIScriptAlias / /var/www/FlaskApp/flaskapp.wsgi
		<Directory /var/www/FlaskApp/FlaskApp/>
			Order allow,deny
			Allow from all
		</Directory>
		Alias /static /var/www/FlaskApp/FlaskApp/static
		<Directory /var/www/FlaskApp/FlaskApp/static/>
			Order allow,deny
			Allow from all
		</Directory>
		ErrorLog ${APACHE_LOG_DIR}/error.log
		LogLevel warn
		CustomLog ${APACHE_LOG_DIR}/access.log combined
</VirtualHost>
   ```
   Enable the virtual host 
   `sudo a2ensite FlaskApp`
   
   Disabling the default apache2 page
   `sudo a2dissite 000-default.conf`
   
  #### Create the .wsgi File
    ```
    cd /var/www/FlaskApp
    sudo nano flaskapp.wsgi 
    ```
   Add the following code
   
   ```
   #!/usr/bin/python
    import sys
    import logging
    logging.basicConfig(stream=sys.stderr)
    sys.path.insert(0,"/var/www/FlaskApp/")

    from FlaskApp import app as application
    application.secret_key = 'Add your secret key'
   ```
   save and exit
   
   Deploying flask app with apache2 is referred from [Digital ocean](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
   
   #### Installing require modules
   You can either install all modules on your machine or create a virtual environment for the project and install the modules
   ` pip install flask sqlalchemy psycopg2 requests oauth2client`
   
   #### Setting up your Google Oauth2
   Login to your [developer console](https://console.developers.google.com) and select your project and edit OAuth details as following
   
   Javascript origin
   `http://ip.xip.io`
   
   redirect URI
   
   `http://ip.xip.io/login`
   
   `http://ip.xip.io/gconnect`
   
   `http://ip.xip.io/callback`
   
   [xip.io](xip.io) is a free DNS which will be the same as using IP address
   
### Install Apache 2
    https://httpd.apache.org/download.cgi

    https://apache-http-server.en.softonic.com
   
   #### Final Step
   Restart your apache2 server
   
   `sudo service apache2 restart`
