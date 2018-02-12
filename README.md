[![Circle CI](https://circleci.com/gh/codeworksio/docker-postgres.svg?style=shield "CircleCI")](https://circleci.com/gh/codeworksio/docker-postgres)&nbsp;[![Size](https://images.microbadger.com/badges/image/codeworksio/postgres.svg)](http://microbadger.com/images/codeworksio/postgres)&nbsp;[![Version](https://images.microbadger.com/badges/version/codeworksio/postgres.svg)](http://microbadger.com/images/codeworksio/postgres)&nbsp;[![Commit](https://images.microbadger.com/badges/commit/codeworksio/postgres.svg)](http://microbadger.com/images/codeworksio/postgres)&nbsp;[![Docker Hub](https://img.shields.io/docker/pulls/codeworksio/postgres.svg)](https://hub.docker.com/r/codeworksio/postgres/)

Docker Postgres
===============

Customised Postgres base image.

Installation
------------

Builds of the image are available on [Docker Hub](https://hub.docker.com/r/codeworksio/postgres/).

    docker pull codeworksio/postgres

Alternatively you can build the image yourself.

    docker build --tag codeworksio/postgres \
        github.com/codeworksio/docker-postgres

Testing
-------

    make build test
