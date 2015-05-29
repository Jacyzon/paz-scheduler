[![Latest Docs](http://img.shields.io/badge/docs-latest-blue.svg)](http://docs.pazscheduler.apiary.io)


# paz-scheduler
=============

Takes apps from your paz service directory and runs them on a CoreOS cluster using Fleet.

API documentation can be generated by running the following command:

```
$ npm run docs
```

And these docs can be served locally by running:
```
$ npm run docs-server
```

...and going to `http://localhost:9002` in the browser to see them.

The API documentation is generated from `apiary.apib`.

## Tests

API functional tests can be found in `test/`.

To run on OS X (w/ Boot2Docker):
```
$ DOCKER_IP=192.168.59.103 npm test
```

Tun run on Linux etc.:
```
$ npm test
```
