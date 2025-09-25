Depends on OS: Ubuntu/Debian vs RHEL/CentOS

Debian/Ubuntu:

apt update && apt upgrade -y
apt install nginx -y
apt remove nginx -y

RHEL/CentOS:

yum install httpd -y
yum remove httpd -y
yum update -y

