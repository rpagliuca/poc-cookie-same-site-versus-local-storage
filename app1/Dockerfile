FROM kyma/docker-nginx
COPY server.key /etc/nginx/ssl/server.key
COPY server.crt /etc/nginx/ssl/server.crt
RUN ln -s /etc/nginx/sites-available/default-ssl /etc/nginx/sites-enabled/default-ssl
COPY public /var/www
