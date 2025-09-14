# Use the latest Nginx as base image
FROM nginx:latest

# Copy the softy-pinko-front-end files to the web server directory
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the custom Nginx configuration file
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf