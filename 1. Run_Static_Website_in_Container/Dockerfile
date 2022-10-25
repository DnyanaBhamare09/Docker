FROM nginx
ENV FRIEND="Dnyandip"
WORKDIR /usr/share/nginx/html
COPY Hello_Docker.html /usr/share/nginx/html

CMD cd /usr/share/nginx/html && sed -e s/Friend/"$FRIEND"/ Hello_Docker.html > index.html ; nginx -g'daemon off;'