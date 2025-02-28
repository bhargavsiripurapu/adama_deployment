# Use an official lightweight web server image
FROM nginx:alpine

# Set working directory
WORKDIR /usr/share/nginx/html

# Copy the HTML file and image into the Nginx HTML directory
COPY login.html index.html
COPY nrl-logo.png .

# Expose the default Nginx port
EXPOSE 80
