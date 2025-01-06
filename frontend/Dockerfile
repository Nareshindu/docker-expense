FROM nginx:latest
COPY code /usr/share/nginx/html
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
RUN rm -rf /etc/nginx/conf.d/default.conf
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
