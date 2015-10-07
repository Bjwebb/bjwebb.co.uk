## Running Jekyll using docker

```
docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -ti -p 127.0.0.1:4000:4000 jekyll/jekyll:stable
```
