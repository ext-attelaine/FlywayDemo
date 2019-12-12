# FlywayDemo

Requires Flyway [Command-line tool](https://flywaydb.org/documentation/commandline/) to be installed.

1. Create db password for docker-compose.yml and conf/flyway.conf
2. Run sql server in docker: docker-compose up -d sqlserver
3. Run first two flyway migrations: flyway -target=2 migrate
4. Get status info (or go check db): flyway info
5. Run rest of the migrations: flyway migrate
6. Get status info (or go check db): flyway info
