FROM php:7.4-cli

EXPOSE 8000
RUN mkdir public
COPY index.php public
WORKDIR /public
CMD ["php", "-S", "0.0.0.0:8000"]
#
# I am lost, how to bind port from host to container in Dockerfile?
# Answer: docker run -p 8080:8000 php-hello-world:ch03
#