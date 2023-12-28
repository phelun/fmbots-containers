# Use the official CentOS 7 base image from Docker Hub
FROM centos:7

# Maintainer information
LABEL maintainer="Your Name <your.email@example.com>"

# Install any necessary software or dependencies
RUN yum -y update && \
    yum -y install httpd && \
    yum clean all

# Set the working directory
WORKDIR /var/www/html

# Copy your application files into the container (assuming you have them in the same directory as the Dockerfile)
COPY . .

# Expose the port your application will listen on (e.g., for an HTTP server)
EXPOSE 80

# Define the command to start your application (e.g., for an HTTP server)
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]

