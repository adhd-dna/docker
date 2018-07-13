# Jekyll docker

Dockerfile for front-end and back-end CI builds.

Alpine based image that can be installed on a Docker enabled CI service to build to generate a [Jekyll](https://jekyllrb.com) site and deploy via rsync. Has been tested with [Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines).

**What's in the box?**
* ruby (v2.3.3)
* bundler (v1.14.3)
* jekyll (v3.4.0)
* node (v6.9.2)
* rsync

Available on Dockerhub at https://hub.docker.com/r/adhddna/jekyll/
