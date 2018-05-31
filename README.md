### Using Docker and Nginx to Host Multiple Websites

- https://blog.ssdnodes.com/blog/tutorial-using-docker-and-nginx-to-host-multiple-websites/
- https://blog.florianlopes.io/host-multiple-websites-on-single-host-docker/
- https://github.com/jwilder/nginx-proxy


### Step 1
We need to first create a Docker network that we will use to bridge all of the containers together.

```sh
$ docker network create nginx-proxy
```

### Step 2

And then run the following `docker-compose` command to get started.
```sh
$ docker-compose up -d
```

