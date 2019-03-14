# Webmin Oneliner
One liner to install Webmin on Ubuntu based servers

## What is Webmin?

http://www.webmin.com/

Webmin is a web-based interface for system administration for Unix. Using any modern web browser, you can setup user accounts, Apache, DNS, file sharing and much more. Webmin removes the need to manually edit Unix configuration files like /etc/passwd, and lets you manage a system from the console or remotely.

## Usage

* SSH into server
* Run the command
* Logon to Webmin

## command

echo "deb http://download.webmin.com/download/repository sarge contrib" | sudo tee -a /etc/apt/sources.list && wget http://www.webmin.com/jcameron-key.asc && sudo apt-key add jcameron-key.asc && sudo apt-get update && sudo apt-get install webmin -y

## Will this change my life?

Yes.

## Will it break anything?

Dunno.
