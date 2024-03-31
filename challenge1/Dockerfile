# Use the official NGINX image as base
FROM nginx:latest

# Remove the default NGINX configuration file
RUN rm /etc/nginx/conf.d/default.conf

# Copy custom NGINX configuration file
COPY nginx.conf /etc/nginx/conf.d/

# Copy website files into the public folder
COPY public /usr/share/nginx/html

EXPOSE 80
