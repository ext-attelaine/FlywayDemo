# FlywayDemo

Requires Flyway [Command-line tool](https://flywaydb.org/documentation/commandline/) to be installed.

1. Run sql server in docker: docker-compose up -d sqlserver
2. Run first two flyway migrations: flyway -target=2 migrate
3. Get status info (or go check db): flyway info
4. Run rest of the migrations: flyway migrate
5. Get status info (or go check db): flyway info
