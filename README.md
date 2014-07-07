graphNav-docker-development
===============

## THIS WILL PULL THE DEVELOPMENT VERSION OF graphNav!!!

A docker image to make using [graphNav](https://github.com/jgillmanjr/graphNav) a snap

## Usage
A little bit of manual intervention will be required for this one.

`docker run -t -i -p 80:80 jgillmanjr/graphnav /bin/bash`

From here, you **WILL** need to edit /app/hostInfo.php to properly reference a Neo4j instance (not included in this image)

Once done: `/run.sh &` once you run that, `CTRL+P CTRL+Q` to detach from the container

From there, verify by connecting to the server running the container on port 80
