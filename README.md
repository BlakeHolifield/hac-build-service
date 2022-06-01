# hac-build-service

Hybrid Application Console Build Service

## Getting started

### Run with webpack proxy

1. ```npm install```

2. ```npm run start:prod:beta```

3. Open the URL listed in the terminal output.


### Update `/etc/hosts`

To use webpack proxy you need to append this to your `/etc/hosts` for auth:

```
127.0.0.1 prod.foo.redhat.com
127.0.0.1 stage.foo.redhat.com
127.0.0.1 qa.foo.redhat.com
127.0.0.1 ci.foo.redhat.com

```

### Testing

`npm run verify` will run `npm run lint` (eslint) and `npm test` (Jest)