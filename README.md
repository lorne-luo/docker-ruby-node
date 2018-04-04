# Ruby + Nodejs Dockerfile

This repository contains a Dockerfile of Ruby, nodejs and npm for Docker's automated build published to the public Docker Hub Registry.

## What's included
- Ruby 2.3.7
- Nodejs 8.11 (LTS version)
- npm

### Installation
1. Install [Docker](https://www.docker.com/).

2. Build an image from Dockerfile: `docker build -t="docker-ruby-node"`)


### Usage

    docker run -it --rm docker-ruby-node

#### Run `ruby`

    docker run -it --rm docker-ruby-node ruby

#### Run `node`

    docker run -it --rm docker-ruby-node node
