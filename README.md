# blog

generated using Luminus version "4.38"

FIXME

## Prerequisites

You will need [Leiningen][1] 2.0 or above installed.

[1]: https://github.com/technomancy/leiningen

## Running

You will need to create a postgres database (in your psql prompt):
```
create user blog with password 'blog'
create database blog with owner blog
```
Also create a dev-config.edn at the root of the project like this one (unzip):

[dev-config.edn.zip](https://github.com/ccosmin/clojure-talk-brujug-2022-blog-sample/files/8812965/dev-config.edn.zip)

To start a web server for the application, run:

    lein run 

## License

Copyright © 2022 FIXME
