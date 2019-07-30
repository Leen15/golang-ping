# Ping Pong Server in Go
A simple ping pong server used for health check proposes: It responses to /ping with a "pong".

## Usage

This webserver works inside docker, so to use it simple run it:

`docker run -d -p 80:80 leen15/golang-ping`

And now it will response to any ping request:

```
$ curl http://0.0.0.0/ping
pong
```

## License

This project is released under the terms of the [MIT license](http://en.wikipedia.org/wiki/MIT_License).
