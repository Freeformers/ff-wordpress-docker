# Freeformers Wordpress Docker

*For local dev work only!*

Provides an easily ran docker container for local Wordpress development. Based on Tutum's image, with increased upload limits.

``` bash
docker run -d --link db:db -e DB_PASS="password" -p 80:80 --name test-wp freeformers/ff-wordpress-docker
```
