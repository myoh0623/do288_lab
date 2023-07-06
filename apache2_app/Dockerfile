FROM httpd:2.4

# Copy Apache configuration file
COPY ./conf/httpd.conf /usr/local/apache2/conf/httpd.conf

# Copy web content
COPY ./public_html/ /usr/local/apache2/htdocs/