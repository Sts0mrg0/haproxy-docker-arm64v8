HAProxy Ubuntu arm64v8 Dockerfile
===============================

This repository contains a **Dockerfile** for building a HAProxy image for arm64v8 (Rock64 etc.) from base Ubuntu Docker
image.  HAProxy is an open source TCP and HTTP load-balancer, HTTP reverse-proxy, reliable, fast and flexible.

Base Docker Image
-----------------

* arm64v8/ubuntu

Installation
------------

1. Install [Docker](https://www.docker.com/)
2. Download [haproxytech/haproxy-arm64v8](https://registry.hub.docker.com/u/haproxytech/haproxy-arm64v8/) image from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull haproxytech/haproxy-arm64v8`
3. Run it: `docker run -d -p 80:80 haproxytech/haproxy-arm64v8`

General container help
----------------------

Run `docker run -ti THIS_IMAGE bash` to obtain interactive shell.
Run `docker exec -ti CONTAINERID container-entrypoint` to access already running container.

To get more help on HAProxy, visit [www.haproxy.org](http://www.haproxy.org/). More detailed documentation
is available at [www.haproxy.org/#docs](http://www.haproxy.org/#docs).

Product Description
-------------------

HAProxy is a free, very fast and reliable solution offering high availability,
load balancing, and proxying for TCP and HTTP-based applications. It is
particularly suited for very high traffic web sites and powers quite a number of
the world's most visited ones. Over the years it has become the de-facto
standard opensource load balancer, is now shipped with most mainstream Linux
distributions, and is often deployed by default in cloud platforms. 
