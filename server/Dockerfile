FROM nginx

COPY nginx.conf /etc/nginx/nginx.conf

RUN apt-get update && apt-get install -y php-fpm

COPY index.php /var/www/html/index.php

CMD ["php-fpm", "-F"]