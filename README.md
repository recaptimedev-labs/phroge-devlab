# `@recaptimedev-labs/phorge-devlab` - test-run or deploy Phorge

Try Phorge on Firebase Studio or use our Docker Compose file here or
at [the source image repo](https://github.com/recaptime-dev/infra-docker-phorge) to deploy to your own infra.

## Get started

The included Composefile has a Caddy container ready for use, alongside the usual containers required (Phorge itself and MariaDB) to run a fresh instance.

```shell
# optional but required if building from source
git clone https://issues.recaptime.dev/source/phorge-docker ./src

# add --build flag to build image from source, otherwise use --pull
docker compose up [--build|--pull]
```

## License

* In this repo: MPL-2.0
* [The repo where builds happen](https://issues.recaptime.dev/source/phorge-docker/): MIT (forked from <https://github.com/wetherc/phorge-docker>)
* [Phorge itself](https://we.phorge.it/source/phorge): Apache
