# Description
Needed a quick and dirty http server that always answers OK on GET and POST

# How to use

## build
> docker build . -t fakeserver

## run

> docker run -d --rm -p 3010:3010 fakeserver

## run on other port

> docker run -d --rm -p 3010:3001 -e "PORT=3001" fakeserver
