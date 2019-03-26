# Example Dockerfile PHP 7

# How to build image?
```{r, engine='bash', count_lines}
$ docker build --no-cache -t gloriapg/php:latest .
```

# How to push my image to private or public registry?
```{r, engine='bash', count_lines}
$ docker login -u user ip-or-domain-registry:port
$ docker push ip-or-domain-registry:port/myuser/php:latest
```

# How to run container?
```{r, engine='bash', count_lines}
$ cd php
$ docker run -d -p 8080:80 gloriapg/php:latest
```
