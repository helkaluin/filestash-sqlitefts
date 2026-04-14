# filestash-sqlitefts
Filestash Docker image built with the sqlite search plugin

This is just my lazy way of automatically building Filestash with SQLite search on GitHub so I could automatically pull it instead of compiling locally.

GitHub Action should build daily, unless I get lazy and forget to re-enable it after it gets automatically disabled after 60 days of inactivity.

[![Docker Build and Publish](https://github.com/helkaluin/filestash-sqlitefts/actions/workflows/docker-build-push.yml/badge.svg)](https://github.com/helkaluin/filestash-sqlitefts/actions/workflows/docker-build-push.yml)

**Docker Pull**

* from GitHub Container Registry:

```
docker pull ghcr.io/helkaluin/filestash-sqlitefts:latest
```
