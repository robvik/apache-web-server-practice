Server version: Apache/2.4.46 (Ubuntu)

# apache-web-server-practice
A practice repository for different apache web server configurations for:
- Webserver
- Reverse proxy
- Load balancer

The configurations focus on:
- Performance
- Security
- Caching
- Bandwidth access control

#### apache commands
- apache2 -h: shows the help menu
- apache2 -v: shows the apache version
- apache2 -V: shows the apache version, build information, and configuration arguments
- apache2ctl -t: tests the apache configuration
- sudo systemctl enable apache2: Enable auto-start at system boot
- sudo systemctl start apache2: Start apache
- sudo systemctl stop apache2: Stop apache
- sudo systemctl reload apache2: Reload apache server configuration
- sudo systemctl restart apache2: Restart apache
- sudo systemctl status apache2: Status apache
