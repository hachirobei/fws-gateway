# Use the official Nginx image as a base
FROM nginx:latest

LABEL maintainer="hachirobei93@gmail.com"

# Copy custom Nginx configuration from the current directory
COPY ../docker/default.conf /etc/nginx/conf.d/default.conf

# Expose port 80
EXPOSE 80

# Nginx will start automatically when the container is run from this image, 
# so no need to specify a CMD or ENTRYPOINT unless you have a custom startup script.