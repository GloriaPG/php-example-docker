# Example Dockerfile PHP 7

# How to build image?
```{r, engine='bash', count_lines}
$ docker build --no-cache -t gloriapg/php:v1.0 .
```

# How to push my image to private or public registry?
```{r, engine='bash', count_lines}
$ docker login -u user ip-or-domain-registry:port
$ docker push ip-or-domain-registry:port/myuser/php:v1.0
```

# How to run container?
```{r, engine='bash', count_lines}
$ cd php
$ docker run -d -p 8080:80 gloriapg/php:v1.0
```
# php-example-docker
