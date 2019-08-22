# Deploy website to AWS EC2

# Step 1 – Installing Nginx

   sudo apt update
   
   sudo apt install nginx


# Step 2 - Checking your Web Server

#  systemctl status nginx

# Step 3 – Managing the Nginx Process

#  To stop your web server: sudo systemctl stop nginx
#  To start the web server when it is stopped: sudo systemctl start nginx
#  To stop and then start the service: sudo systemctl restart nginx
#  By default, Nginx is configured to start automatically when the server boots. If this is not what you want, you can disable this behavior: sudo systemctl disable nginx
#  To re-enable the service to start up at boot, you can type: sudo systemctl enable nginx
