# headful-puppeteer-docker

Whether headless or headful, getting Puppeteer to run inside a Docker container was pretty trivial. The challenge was displaying the GUI in headful mode.

After piecing together a few different resources, I decided to create a quick demo repo.

## Installation

You will need to have [`Docker Compose`](https://docs.docker.com/compose/install/) and/or [`Docker`](https://docs.docker.com/get-docker/) installed to use this.

## Docker

Build with:

`$ docker build -t headful-puppeteer-docker .`

Run with:

`$ docker run -p 5900:5900 headful-puppeteer-docker`

Stop with:

`$ docker stop headful-puppeteer-docker`

## Docker Compose

Build with:

`$ docker-compose build`

Run with:

`$ docker-compose up`

Stop with:

`$ docker-compose stop`
