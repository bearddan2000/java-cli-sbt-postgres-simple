# java-cli-sbt-postgres-simple

## Description
Creates a small database table
called `dog`. All output normally
seen in a terminal will be in `java-srv/log` which will dump to the screen. The project may seem to hang but the logs from the container must be written to the project this can take up to 3 min.

## Tech stack
- java
- sbt
  - log4j
  - postgres driver

## Docker stack
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10
- postgres:alpine

## To run
`sudo ./install.sh -u`
Creates java-srv/log

## To stop
`sudo ./install.sh -d`
Removes java-srv/log

## For help
`sudo ./install.sh -h`

## Credit
https://github.com/htorun/dbtableprinter

## java-cli specific search
- [Search by sbt](https://github.com/bearddan2000?tab=repositories&q=java-cli-sbt&type=&language=&sort=)
- [Search by postgres](https://github.com/bearddan2000?tab=repositories&q=java-cli-postgres&type=&language=&sort=)
- [Search by simple](https://github.com/bearddan2000?tab=repositories&q=java-cli-simple&type=&language=&sort=)
- [Search by log4j](https://github.com/bearddan2000?tab=repositories&q=java-cli-log4j&type=&language=&sort=)
- [Search by driver](https://github.com/bearddan2000?tab=repositories&q=java-cli-driver&type=&language=&sort=)

## General search
- [Search by java](https://github.com/bearddan2000?tab=repositories&q=java&type=&language=&sort=)
- [Search by cli](https://github.com/bearddan2000?tab=repositories&q=cli&type=&language=&sort=)
- [Search by sbt](https://github.com/bearddan2000?tab=repositories&q=sbt&type=&language=&sort=)
- [Search by postgres](https://github.com/bearddan2000?tab=repositories&q=postgres&type=&language=&sort=)
- [Search by simple](https://github.com/bearddan2000?tab=repositories&q=simple&type=&language=&sort=)
- [Search by log4j](https://github.com/bearddan2000?tab=repositories&q=log4j&type=&language=&sort=)
- [Search by driver](https://github.com/bearddan2000?tab=repositories&q=driver&type=&language=&sort=)
