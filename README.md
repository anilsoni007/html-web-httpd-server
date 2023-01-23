## html-web-httpd-server
###### this is a simple httpd web server code to host a sample website.

**Required tools for this setup**
> linux server with git and httpd package on it.

## Step-1
```
git clone https://github.com/anilsoni007/html-web-httpd-server.git
```

## Step-2
```
move the content of dir html-web-httpd-server into /var/www/html document root directory
cd html-web-httpd-server/
sudo cp -pr ./* /var/www/html
sudo systemctl start httpd
```
## Step-3
access the server using 
```
<ServerIP:80>
```

