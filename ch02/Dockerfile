FROM php:7.4-cli
RUN mkdir public
COPY index.php public
WORKDIR /public
CMD php -S localhost:80

#
# I am lost, how to bind port from host to container in Dockerfile?
#
#