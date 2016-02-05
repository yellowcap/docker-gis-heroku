# GIS Docker Image

This repository contains a Python docker image, for use with Heroku and the
[heroku-docker](https://github.com/heroku/heroku-docker) CLI plugin.

The image is extended with GIS libraries (gdal, geos, proj, and mapserver) and
a Nodejs install. It is a mixture between the
[docker-python](https://github.com/heroku/docker-python) and
[docker-nodejs](https://github.com/heroku/docker-nodejs) images.

[Image available on Dockerhub](https://hub.docker.com/r/yellowcap/docker-gis-heroku/).
