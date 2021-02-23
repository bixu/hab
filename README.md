# hab

Run the Habitat Supervisor in a "shim" container.

## Running in Docker

Instructions for using the container based on this repo are [here](https://github.com/users/bixu/packages/container/package/hab).

## Basic Usage

The simplest way to use this "shim" container is to pass a command like this as your Docker Entrypoint:

```shell
hab sup run core/redis
```

See [the official documentation](https://www.habitat.sh/docs) for more detail.
