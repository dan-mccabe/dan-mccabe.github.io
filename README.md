# Dan McCabe's Personal Website

This repository stores my personal website. It is based on [cvless](https://jamstackthemes.dev/theme/jekyll-cvless/),  a theme for static websites built with Jekyll, and deploys automatically to [https://dan-mccabe.github.io](https://dan-mccabe.github.io) using GitHub pages. You are free to adapt it for your own use under the MIT License.

## Installation
1.  Clone this repository.
2.  Rename it to `[username].github.io`.
3.  Start editing!


## Local Development
### Using Jekyll and Bundle
I have developed locally using:
* `bundle install`
* `bundle exec jekyll serve`

Alternatively, you can use Docker as copied from the cvless docs below.

### Using Docker
This repo includes a docker-compose file that allows you to quickly setup a container running Jekyll. If you don't already have Docker and docker-compose installed, you can install them using the following guides:

**Install Guides**
* [Docker](https://docs.docker.com/get-docker/)
* [docker-compose](https://docs.docker.com/compose/install/)

To start the container simply run:

```
docker-compose up
```

Alternatively you can run the container without docker-compose using this command on iOS/Linux:

```
docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
```
