# Use Alpine Linux as the base image
FROM alpine:latest

# Install Nginx and create necessary directories
RUN apk update && apk add nginx && mkdir -p /run/nginx

# Copy a custom Nginx configuration file to replace the default one
# COPY nginx.conf /etc/nginx/nginx.conf

# # Expose port 80 for web traffic
# EXPOSE 80

# # Start Nginx in the foreground when a container is run
# CMD ["nginx", "-g", "daemon off;"]

