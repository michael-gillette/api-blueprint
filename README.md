# Name

API Blueprint Compose Stack

# Summary

Starts two services based on a single API Blueprint. One service provides a stub
server. The second service provides documentation as interpreted by Apiary.

# Getting Started

Make any changes you want to `blueprint.apib`. Both the stub server and the
documentation server are configured to watch for changes to the file.

## Requirements

+ `docker`
+ `docker-compose`

## Start

Start the services with a simple up.

```
$ docker-compose up
```

## Connect

**stub server**

Available on port 5000 of your docker host.

**documentation server**

Available on port 4000 of your docker host.

# Open Issues

- At this time, the documentation server does not send example requests to the
  stub server.
