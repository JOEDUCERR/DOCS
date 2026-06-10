# DOCS
A reliable and extremely lightweight Documentation Management System.

## Installation of repo with requirements
```
sudo apt install apache2

cd /var/www

git clone <repo-name>

cd DOCS
```

## Webpage Setup using Apache2
```
sudo nano /etc/apache2/sites-available/DOCS.conf
```
* write a Virtual Host file in DOCS.conf

Finally, check if your webpage is running
```
sudo systemctl enable apache2

sudo systemctl start apache2

sudo en2site DOCS.conf
```
