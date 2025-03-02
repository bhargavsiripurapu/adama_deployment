# Use an official lightweight web server image
FROM nginx:alpine

# Set working directory
WORKDIR /usr/share/nginx/html

# Copy the HTML file and image into the Nginx HTML directory
COPY adama.html index.html
COPY adama.svg .
COPY Farmer with Sugar Cane.webp

# Expose the default Nginx port
EXPOSE 80
