# headless-chrome-node

This is a docker image with node and headless chrome installed. It uses `debian:stable-slim` as the base image. This is based on karanjthakkar's [headless-chrome-node-docker](https://github.com/karanjthakkar/headless-chrome-node-docker) image.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [Docker CE](https://docs.docker.com/install/)

### Installing

To pull the image locally:

```sh
$ docker pull switchspan/headless-chrome-node:latest
```

You can also use the image in the `FROM` command of your `Dockerfile`.

## Built With

- [Docker](http://www.docker.com/) - The containerization used

## Contributing

TBD

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

- **Ken Taylor** - _Initial work_ - [switchspan](https://github.com/switchspan)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- [Geek Karan's original headless-chrome-node-docker](https://github.com/karanjthakkar/headless-chrome-node-docker)
