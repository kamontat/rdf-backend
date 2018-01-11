# rdf-backend - Random Food (Backend)

## Badge

| Badge | Description |
| ----- | ----------- |
| [![Codecov](https://img.shields.io/codecov/c/github/kamontat/rdf-backend.svg)](https://codecov.io/github/kamontat/rdf-backend) | code coverage, use **codecov** |
| [![Coveralls github](https://img.shields.io/coveralls/github/kamontat/rdf-backend.svg)](https://coveralls.io/github/kamontat/rdf-backend) | code coverage, use **coverall** |
| [![CircleCI](https://img.shields.io/circleci/project/github/kamontat/rdf-backend.svg)](https://circleci.com/gh/kamontat/rdf-backend) | testing CI, use **CircleCI** |
| [![Code Climate](https://img.shields.io/codeclimate/maintainability/kamontat/rdf-backend.svg)](https://codeclimate.com/github/kamontat/rdf-backend) | analysis code and maintainability, use **code climates** |
| [![Code Climate](https://img.shields.io/codeclimate/issues/github/kamontat/rdf-backend.svg)](https://codeclimate.com/github/kamontat/rdf-backend/issues) | code issues or problem, use **code climates** |

## Available command

### Start server

| Available command         | Description                                            |
| ------------------------- | ------------------------------------------------------ |
| `npm` start               | start server with *default* env                        |
| `npm` run start:watch     | start server with *default* env and watch file changes |
| `npm` run start:dev       | start server with *develop* env                        |
| `npm` run start:dev:watch | start server with *develop* env and watch file changes |
| `npm` run start:prod      | start server with *prouction* env                      |

### Testing

| Available command    | Description                                             |
| -------------------- | ------------------------------------------------------- |
| `npm` run test:mocha | run mocha test without any configuration                |
| `npm` test           | run **test:mocha** in *test* env                        |
| `npm` run test:watch | run **test:mocha** in *test* env and watch file changes |

### Code coverage

| Available command   | Description                                               |
| ------------------- | --------------------------------------------------------- |
| `npm` run cov       | run test and sent the report to **coveralls**             |
| `npm` run cov:check | run checker coverage, all of this should more and **70%** |
|                     | *lines*, *functions*, *statements*, and *branches*        |

### CI testing

| Available command   | Description                                                                 |
| ------------------- | --------------------------------------------------------------------------- |
| `npm` run ci:test   | run test, This must run in **CircleCI** only                                |
| `npm` run ci:report | run test and sent report to **codecov**, This must run in **CircleCI** only |

### Monitoring

| Available command | Description                                                       |
| ----------------- | ----------------------------------------------------------------- |
| monitor:start     | start monitor server, use `pm2` command                           |
| monitor:stop      | stop monitor server, use `pm2` command                            |
| monitor:show      | stop monitor information, use `pm2` command                       |
| monitor:restart   | restart server and monitor, use `pm2` command                     |
| monitor:delete    | delete server process, use `pm2` command                          |
| monitor:log       | show server log, use `pm2` command. `--lines` to specify out line |

I use [keymetrics](https://app.keymetrics.io/#/bucket/5a577eee62ecfc0d06830be1/dashboard) as monitor.

### Production

| Available command    | Description                       |
| -------------------- | --------------------------------- |
| `npm` run start:prod | start server with *prouction* env |
