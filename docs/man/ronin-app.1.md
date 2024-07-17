---
layout: page
title: Docs - Man Pages - ronin-app
---

## NAME

ronin-app - A local web interface for Ronin

## SYNOPSIS

`ronin-app` [*options*] [*COMMAND*]

## DESCRIPTION

Starts the local Ronin web application.

## OPTIONS

`-H`, `--host` *IP*
: The IP address to listen on. Defaults to `localhost` if not specified.

`-p`, `--port` *PORT*
: The port to listen on. Defaults to `1337` if not specified.

`--db` *NAME*
: Specifies the `ronin-db` database name for the app to connect to.

`--db-uri` *URI*
: Specifies a database URI for the app to connect to.

  * **sqlite3**: `sqlite3:relative/path.db` or `sqlite3:///absolute/path.db`
  * **mysql**: `mysql://user:password@host/database`
  * **postgres**: `postgres://user:password@host/database`

`-V`, `--version`
: Prints the `ronin-app` version.

`-h`, `--help`
: Prints help information.

## ENVIRONMENT

*HOME*
: Alternate location for the user's home directory.

*XDG_CONFIG_HOME*
: Alternate location for the `~/.config` directory.

*XDG_DATA_HOME*
: Alternate location for the `~/.local/share` directory.

## FILES

`~/.local/share/ronin-db/database.sqlite3`
: The default sqlite3 database file.

`~/.config/ronin-db/database.yml`
: Optional database configuration.

## AUTHOR

Postmodern <postmodern.mod3@gmail.com>


