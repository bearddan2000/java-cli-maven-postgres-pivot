# java-cli-maven-postgres-pivot

## Description
Creates a small database table
called `dog`. This table, `dog`, has been normalized to 3NF.
Two new tables have been added, `breedLookup` and `colorLookup`.
Creates a new table `dog_expanded` that joins
`dog`, `breedLookup` and `colorLookup`. Added clustered indexes on
`dog`.breedId and `dog`.colorId. Turned `dog_expanded` into a view with an
implicit index on `dog_expanded`.id. Using a case statement with the aggregate function
COUNT, create a new view `breed_count`. All output normally
seen in a terminal will be in `java-srv/log` which will dump to the screen. The project may seem to hang but the logs from the container must be written to the project this can take up to 3 min.

## Tech stack
- java
- maven
  - log4j
  - postgres driver

## Docker stack
- maven:3-openjdk-17
- postgres

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
- [Search by maven](https://github.com/bearddan2000?tab=repositories&q=java-cli-maven&type=&language=&sort=)
- [Search by postgres](https://github.com/bearddan2000?tab=repositories&q=java-cli-postgres&type=&language=&sort=)
- [Search by pivot](https://github.com/bearddan2000?tab=repositories&q=java-cli-pivot&type=&language=&sort=)
- [Search by log4j](https://github.com/bearddan2000?tab=repositories&q=java-cli-log4j&type=&language=&sort=)
- [Search by driver](https://github.com/bearddan2000?tab=repositories&q=java-cli-driver&type=&language=&sort=)

## General search
- [Search by java](https://github.com/bearddan2000?tab=repositories&q=java&type=&language=&sort=)
- [Search by cli](https://github.com/bearddan2000?tab=repositories&q=cli&type=&language=&sort=)
- [Search by maven](https://github.com/bearddan2000?tab=repositories&q=gradle&type=&language=&sort=)
- [Search by postgres](https://github.com/bearddan2000?tab=repositories&q=postgres&type=&language=&sort=)
- [Search by pivot](https://github.com/bearddan2000?tab=repositories&q=pivot&type=&language=&sort=)
- [Search by log4j](https://github.com/bearddan2000?tab=repositories&q=log4j&type=&language=&sort=)
- [Search by driver](https://github.com/bearddan2000?tab=repositories&q=driver&type=&language=&sort=)
