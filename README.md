# Play-Starter

A simple Java webapp in Play framework.

## Prerequisites

* [JDK 1.8](https://www.java.com/en/download/faq/develop.xml)
* [Eclipse](https://eclipse.org/downloads/) or [Spring Tools Suite](https://spring.io/tools) (Optional)
* [Docker](https://docs.docker.com/engine/installation/) (Optional)
* [SBT 1.0](http://www.scala-sbt.org/download.html) (Optional)

## Run Manually

1. Download code `git clone https://github.com/amdelamar/play-starter`
1. `cd play-starter`
1. Run build `./sbt compile` (Also `test` for unit tests)
1. Run `./sbt run`
1. Visit [http://localhost:9000/](http://localhost:9000/) to see the app running.

<!--
## Run in Docker

1. Download code `git clone https://github.com/amdelamar/play-starter`
1. `cd play-starter`
1. Run build `./sbt`
1. Build image `docker build -t play .`
1. Run container `docker run -p 9000:9000 play`
1. Visit [http://localhost:9000/](http://localhost:9000/) to see the app running.
-->

## License

[MIT](/LICENSE)
