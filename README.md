# Travis CI Build Stages Demo for docker

[![Build Status](https://travis-ci.org/kealan/build-stages-docker.svg?branch=master)](https://travis-ci.org/kealan/build-stages-docker)

# Quick start

Install travis cli

    gem install travis

Add you secure environmental values.

    travis encrypt DOCKER_USERNAME=username --add
    travis encrypt DOCKER_PASSWORD=password --add

Create "travis-ci-build-stages-demo" on docker hub
