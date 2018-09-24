# vuecs

[![Join the chat at https://gitter.im/CitizenScienceCenter/frontend](https://badges.gitter.im/CitizenScienceCenter/frontend.svg)](https://gitter.im/CitizenScienceCenter/frontend?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

> CCCS Sample Client App

## Running

### Development

* `npm run dev` (or select a different environment)

### Docker

* `docker build . -t <TAG>`
* `docker run <TAG> -p PORT:PORT`
* Load on the port specified (if using the backend in Docker, you will need to expose this as well)

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
