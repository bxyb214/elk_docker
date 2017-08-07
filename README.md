# bxyb214 Console

[![Build Status][travis-image]][travis-url]
[![Join the chat at https://gitter.im/bxyb214/bxyb214-console](https://badges.gitter.im/bxyb214/bxyb214-console.svg)](https://gitter.im/bxyb214/bxyb214-console?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This is the [bxyb214](http://bxyb214.github.io/) Console, based on the [ELK Stack](https://www.elastic.co/products). It provides a default configuration to get started with logs and metrics monitoring with ELK as well as some nice dashboards.

Please refer to the [bxyb214 Monitoring Documentation](http://bxyb214.github.io/monitoring) for instructions on how to set up the bxyb214 Console.

[travis-image]: https://travis-ci.org/bxyb214/bxyb214-console.svg?branch=master
[travis-url]: https://travis-ci.org/bxyb214/bxyb214-console

## Quick Start

Start everything with `docker-compose up -d`, access Kibana at [localhost:5601](http://localhost:5601) and Zipkin at [localhost:9411](http://localhost:9411)
Once everything is up, load the dashboards with : `docker-compose up bxyb214-import-dashboards`

## Contributing

PRs are welcome ! When contributing, make sure you force build and restart everything with `docker-compose down && docker-compose build --no-cache && docker-compose up`.

