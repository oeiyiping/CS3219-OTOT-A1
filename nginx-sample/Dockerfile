# Specify nginx image to build from
FROM nginx

# Remove existing nginx.conf
RUN rm /etc/nginx/nginx.conf

# Copy index.html to be served to server
COPY index.html /usr/share/nginx/html

# Copy new nginx.conf to server
COPY nginx.conf /etc/nginx