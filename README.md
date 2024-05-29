# vagrant-docker-provider-ubuntu-latest
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

An ubuntu:latest docker image to use as a vagrant docker provider.

To use:
1. Install docker.
2. Install vagrant.
3. Save a Vagrantfile that references this image. Use the example in this repo. Then "vagrant up" to start an environment.

To build the image locally:
1. `docker build -t vagrant-docker-provider-ubuntu .`
