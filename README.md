# HASQLite2MariaDB

## Goal

Tool to migrate a home assistant sqlite file to a mariadb instance

## Usage
Take a copy of the home-assistant_v2.db to the root of this project
Change the connection parameters in the `command:` line to the used mariadb instance

## Testing
When no mariadb instance exists, or you just want to try it out, a default mariadb docker container is started too.
