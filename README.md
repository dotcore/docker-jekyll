# Jekyll with rmagick support

Docker Hub: <https://hub.docker.com/r/dotcore/jekyll/>

Use example:

```
docker run --rm -v "$PWD:/src" dotcore/jekyll build
```

For convenience you could add an alias to:
```
alias jekyll='docker run --rm -v "$PWD:/src" -p 4000:4000 dotcore/jekyll'
```

Run jekyll build:
```
jekyll build
```

Run jekyll serve:
```
jekyll serve -H 0.0.0.0
```
