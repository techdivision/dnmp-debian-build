# dnmp debian
[![Docker Hub](https://img.shields.io/badge/docker-ready-blue.svg)](https://registry.hub.docker.com/u/techdivision/dnmp-debian/)
[![Docker Automated build](https://img.shields.io/docker/automated/techdivision/dnmp-debian-build.svg)]()

A docker image based on debian to build software

## Usage
```bash
alias d='docker run --rm -it -v $HOME:/root/ -v $PWD:/build dnmp-build $@'

cd ~/Repositories/YOUR-PROJECT
d composer install
d npm install
```

## Tools
- php v7
- composer
- nodejs
- compass
- sass
- gulp
