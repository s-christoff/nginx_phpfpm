Goal: Using Docker Compose set up PHP FPM and throw Nginx in front of it.

To Do:
- Create the docker-compose.yml to set up Nginx and PHP FPM [Following this Guide](http://geekyplatypus.com/dockerise-your-php-application-with-nginx-and-php7-fpm/)
- Test it


Questions I had:

What is the different between build and image?

- [This article](https://stackoverflow.com/questions/34316047/difference-between-image-and-build-within-docker-compose) says image means it will run a container based off the image, but build will build the image that is specified in the directory and then run it.
