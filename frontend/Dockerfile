FROM          nginx
RUN           rm -rf /usr/share/nginx/html/*
COPY          nginx.conf /etc/nginx/nginx.conf
COPY          roboshop.conf /etc/nginx/conf.d/default.conf
COPY          static/ /usr/share/nginx/html/
