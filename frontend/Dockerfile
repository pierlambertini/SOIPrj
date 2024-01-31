FROM httpd:2.4
RUN echo "frontend localhost" >> ./todo-app/my-httpd.conf
COPY ./todo-app/ /usr/local/apache2/htdocs/
COPY ./my-httpd.conf /usr/local/apache2/conf/httpd.conf
