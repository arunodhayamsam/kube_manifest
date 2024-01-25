FROM nginx:latest
RUN chgrp -R 777 /var/cache/nginx /var/run /var/log/nginx && \
    chmod -R 770 /var/cache/nginx /var/run /var/log/nginx
ENTRYPOINT ["nginx", "-g", "daemon off;"]