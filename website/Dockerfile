# Use the official Nginx image
FROM nginx:alpine

# Set working directory inside container
WORKDIR /usr/share/nginx/html

# Remove default Nginx index page
RUN rm -rf ./*

# Copy your HTML and CSS files into the container
COPY index.html .
COPY style.css .

# Expose port 80
EXPOSE 80

# Nginx runs automatically with this base image
