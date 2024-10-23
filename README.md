Just launch
After install need to change /etc/httpd/conf/httpd.conf port listenning 443
Add firewalld rules if needed

To fix : systemctl service misp-workers doesn't work, need to start with command line /var/www/MISP/app/Console/worker/start.sh

