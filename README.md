A demo of running a Python command interactively (using `input()`) in Docker.

Pure Docker:

```
docker build . -t python-foreground
docker run -it python-foreground
> What is your name?
> Stanislav
> Hello Stanislav!
```

With docker-compose: 

```
docker-compose build
docker-compose run interactive
> What is your name?
> Stanislav
> Hello Stanislav!
```