# Command to build container
``
docker build -t webserver .
``
# Command to start container
``
docker run -it --rm -d -p 8080:80 --name web webserver
``