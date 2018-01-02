# mesos-build-playground

CentOS 7 build environment for Apache Mesos.

## Building

Following [the Apache Mesos build instructions](https://mesos.apache.org/documentation/latest/building/):

```
$ wget https://www.apache.org/dist/mesos/1.4.1/mesos-1.4.1.tar.gz
$ tar xzvf mesos-1.4.1.tar.gz
$ cd mesos-1.4.1
$ ./bootstrap
$ mkdir build
$ cd build
$ ../configure
$ make -j8
```

You should now have a built copy of Apache Mesos 1.4.1. On an Intel i7 7700K at stock speeds, I'm able to build from
scratch in approximately 20 minutes.

## License

Licensed at your discretion under either:

 - MIT ([`./LICENSE-MIT`](./LICENSE-MIT))
 - Apache License, Version 2.0 ([`./LICENSE-APACHE`](./LICENSE-APACHE))
