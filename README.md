# we-care-you

[![Go](https://github.com/RainbowDashy/we-care-you/actions/workflows/go.yml/badge.svg)](https://github.com/RainbowDashy/we-care-you/actions/workflows/go.yml)

## Start with Docker

First, generate the database:

```shell
make
```

Second, build the docker image:

```shell
docker build . -t we-care-you
```

Then, run the container:
```shell
docker run -p 8080:8080 -v $PWD/data.db:/we-care-you/data.db we-care-you
```


## About the project name

It's a meme, and just for fun :D.

![who-cares](https://user-images.githubusercontent.com/12185797/162921900-3f6e8b68-d4dd-466c-a560-6d6fce19b9df.jpeg)

![sh-cares](https://user-images.githubusercontent.com/12185797/162921955-d7c542dc-0691-46d3-b853-40fd7a829201.jpeg)
