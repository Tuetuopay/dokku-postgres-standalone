# dokku-postgres-standalone

dokku-postgres-standalone is a plugin for [dokku][dokku] that provides Postgres
server to your apps, with a single, external, Postgres instance. This would be
used if you have a dedicated database machine.

This is compatible with dokku 0.3.26+.

## Installation

```shell
# dokku 0.3.26
$ git clone https://github.com/Tuetuopay/dokku-postgres-standalone.git /var/lib/dokku/plugins/psql-standalone
$ dokku plugins-install

# dokku 0.4+
$ dokku plugin:install https://github.com/Tuetuopay/dokku-postgres-standalone.git
```

## Commands

```shell
$ dokku help psql
# TODO
```

## License

This plugin is released under the MIT license. See the file [LICENSE](LICENSE)

