FROM nginx
COPY index.html /usr/share/nginx/html/dashboard/
COPY loader.svg /usr/share/nginx/html/dashboard/assets/branding/
COPY branding.css /usr/share/nginx/html/dashboard/assets/branding/

# and dump in the configuration we want..
COPY nginx.conf /etc/nginx/
COPY default.conf /etc/nginx/conf.d/


