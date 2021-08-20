# grpc-java-bazel minimal example

This project shows a minimal, standalone setup for using grpc-java with bazel.

```
bazel build //...
# start server
./bazel-bin/src/main/java/io/grpc/examples/helloworld/server
# (in different tab) start client
./bazel-bin/src/main/java/io/grpc/examples/helloworld/client
```

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for details.

## License

Apache 2.0; see [`LICENSE`](LICENSE) for details.

## Disclaimer

This project is not an official Google project. It is not supported by
Google and Google specifically disclaims all warranties as to its quality,
merchantability, or fitness for a particular purpose.
