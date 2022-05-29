FROM nginx:1.15.8

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/

RUN rm /etc/nginx/conf.d/default.conf
COPY project.conf /etc/nginx/conf.d/

#COPY certs/fullchain.pem /etc/nginx/ssl/certs/fullchain.pem
#COPY certs/privkey.pem /etc/nginx/ssl/certs/privkey.pem