# Use an official Nginx image as the base image
FROM nginx:alpine

# Copy the static HTML file to the default Nginx public directory
COPY index.html /usr/share/nginx/html/
COPY nginx.conf /etc/nginx/

# Expose port 80 to the outside world
EXPOSE 9080

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
