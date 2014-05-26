[![Build Status](https://travis-ci.org/alexec/docker-java-orchestration.svg?branch=master)](https://travis-ci.org/alexec/docker-java-orchestration)

A small library to orchestrate groups of Docker containers using YAML configuration.

Change Log
---
1.0.2
* Pings containers to see if they are up before returning.
* Added a method the see if the container group is running.
* Will not attempt to start a running container (more idempotent).
