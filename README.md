# similartaste

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lernajs.io/)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com) [![Build Status](https://travis-ci.org/happyname0617/similartaste.svg?branch=master)](https://travis-ci.org/happyname0617/similartaste)

find similar food taste people for local food

## development

### install all packages

```yarn```

```yarn bootstrap```

### build api server

```yarn buid```

### run application in dev mode

```yarn dev```

### clean all projects (npm_modules)

```yarn clean```

## docker

### client

#### prouction mode

    cd packages/client
    docker build -t similartaste-client .
    docker run -p 80:80 similartaste-client

#### development mode

    cd packages/client
    docker-compose up