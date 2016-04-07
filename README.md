# docker-hugo

Usage:

```Dockerfile
FROM ctrlok/hugo
ADD . /site
WORKDIR /site
RUN hugo
VOLUME /site/public
```

