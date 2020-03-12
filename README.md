# Angular docker starter

This is a angular starter application generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.5, deployed by Docker.

## Development server

You can run development environment by command:
`docker run -u $(id -u) --rm -p 4200:4200 -v "$PWD":/app trion/ng-cli ng serve --host 0.0.0.0`
    or use docker compose:
`docker-compose up`


## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
To gen more about the Docker visit [Docker get started website](https://www.docker.com/get-started).
