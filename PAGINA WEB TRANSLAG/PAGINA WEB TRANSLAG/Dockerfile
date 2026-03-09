FROM nginx:alpine

# Copy static assets into nginx
COPY . /usr/share/nginx/html

# Replace the default configuration with our template config
COPY default.conf.template /etc/nginx/templates/default.conf.template
