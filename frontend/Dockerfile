FROM nginx:latest
RUN rm -rf /etc/nginx/conf.d/default.conf
RUN rm -rf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf
