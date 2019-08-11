# serverless-offline-schedule

[![Coverage Status](https://coveralls.io/repos/github/Meemaw/serverless-offline-schedule/badge.svg?branch=master)](https://coveralls.io/github/Meemaw/serverless-offline-schedule?branch=master) [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

## Install Plugin

`npm install --save-dev serverless-offline-schedule`

Then in `serverless.yml` add following entry to the plugins array: `serverless-offline-schedule`

```yml
plugins:
  - serverless-offline-schedule
```

## Using the Plugin

#### Standalone process

```sh
λ → sls schedule
```

#### Part of serverless-offline

`serverless-offline-schedule` will automatically hook into `serverless-offline` start command hook.

```sh
λ → sls offline
...
Serverless: Scheduling [my-function] with [*/1 * * * *]
```
