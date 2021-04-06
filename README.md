# proxy-validator
This Repo will validate the OPEN API - 3.0 Spec against the incoming request and will make sure we have the updated documentation all the time for reference.

## Build it using node or docker
* Build the node module manually
```
npm install
```

* Run a node proxy
```
node proxy.js
```

* The port in which the proxyvalidator will run is 9090 by default.

* Build using a docker container
```
docker build -t tagName:version .
```

* Run a docker image for testing
```
docker run -p 9090:9090 -d tagName:version
```