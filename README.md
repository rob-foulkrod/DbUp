DbUp is a set of .NET libraries that helps you to deploy changes to different databases like SQL Server. It tracks which
SQL scripts have been run already, and runs the change scripts that are needed to get your database up to date.

## This project has been approved by Felipe and Rob.

# Documentation

To learn more about DbUp check out the [documentation](https://dbup.readthedocs.io/en/latest/).

# Status

| Package          |                                                                                                                                                                                                                                                      | Stable                                                                                                                                      | Latest Stable                                                                                                    | Latest Prerelease                                                                                                       | Issues                                                                                                          | Pull Requests                                                                                                     |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| Documentation    |                                                                                                                                                                                                                                                      | [![Documentation Status](https://readthedocs.org/projects/dbup/badge/?version=latest)](https://dbup.readthedocs.io/en/latest/?badge=latest) |                                                                                                                  |                                                                                                                     |                                                                                                                 |                                                                                                                   |
| DbUp-Core        | [![GitHub Actions](https://img.shields.io/github/actions/workflow/status/DbUp/DbUp/main.yml?branch=main)](https://github.com/DbUp/DbUp/actions/workflows/create-draft-release.yml)                                                                   | [![NuGet](https://img.shields.io/nuget/dt/DbUp.svg)](https://www.nuget.org/packages/dbup)                                                   | [![NuGet](https://img.shields.io/nuget/v/DbUp-core.svg)](https://www.nuget.org/packages/DbUp-core)               | [![NuGet](https://img.shields.io/nuget/vpre/DbUp-core.svg)](https://www.nuget.org/packages/dbup)                    | [![view](https://img.shields.io/github/issues/DbUp/DbUp)](https://github.com/DbUp/DbUp)                         | [![view](https://img.shields.io/github/issues-pr/DbUp/DbUp)](https://github.com/DbUp/DbUp)                        |
| DbUp-SqlServer   | [![GitHub Actions](https://img.shields.io/github/actions/workflow/status/DbUp/dbup-sqlserver/main.yml?branch=main)](https://github.com/DbUp/dbup-sqlserver/actions/workflows/main.yml)                                                               | [![NuGet](https://img.shields.io/nuget/dt/dbup-sqlserver.svg)](https://www.nuget.org/packages/dbup-sqlserver)                               | [![NuGet](https://img.shields.io/nuget/v/dbup-sqlserver.svg)](https://www.nuget.org/packages/dbup-sqlserver)     | [![NuGet](https://img.shields.io/nuget/vpre/dbup-sqlserver.svg)](https://www.nuget.org/packages/dbup-sqlserver)     | [![view](https://img.shields.io/github/issues/DbUp/dbup-sqlserver)](https://github.com/DbUp/dbup-sqlserver)     | [![view](https://img.shields.io/github/issues-pr/DbUp/dbup-sqlserver)](https://github.com/DbUp/dbup-sqlserver)    |
| DbUp-MySql       | [![GitHub Actions](https://img.shields.io/github/actions/workflow/status/DbUp/dbup-mysql/main.yml?branch=main)](https://github.com/DbUp/dbup-mysql/actions/workflows/main.yml)                                                                       | [![NuGet](https://img.shields.io/nuget/dt/dbup-mysql.svg)](https://www.nuget.org/packages/dbup-mysql)                                       | [![NuGet](https://img.shields.io/nuget/v/dbup-mysql.svg)](https://www.nuget.org/packages/dbup-mysql)             | [![NuGet](https://img.shields.io/nuget/vpre/dbup-mysql.svg)](https://www.nuget.org/packages/dbup-mysql)             | [![view](https://img.shields.io/github/issues/DbUp/dbup-mysql)](https://github.com/DbUp/dbup-mysql)             | [![view](https://img.shields.io/github/issues-pr/DbUp/dbup-mysql)](https://github.com/DbUp/dbup-mysql)            |
| DbUp-SQLite      | [![GitHub Actions](https://img.shields.io/github/actions/workflow/status/DbUp/dbup-sqlite/main.yml?branch=main)](https://github.com/DbUp/dbup-sqlite/actions/workflows/main.yml)                                                                     | [![NuGet](https://img.shields.io/nuget/dt/dbup-sqlite.svg)](https://www.nuget.org/packages/dbup-sqlite)                                     | [![NuGet](https://img.shields.io/nuget/v/dbup-sqlite.svg)](https://www.nuget.org/packages/dbup-sqlite)           | [![NuGet](https://img.shields.io/nuget/vpre/dbup-sqlite.svg)](https://www.nuget.org/packages/dbup-sqlite)           | [![view](https://img.shields.io/github/issues/DbUp/dbup-sqlite)](https://github.com/DbUp/dbup-sqlite)           | [![view](https://img.shields.io/github/issues-pr/DbUp/dbup-sqlite)](https://github.com/DbUp/dbup-sqlite)          |
| DbUp-PostgreSQL  | [![GitHub Actions](https://img.shields.io/github/actions/workflow/status/DbUp/dbup-postgresql/main.yml?branch=main)](https://github.com/DbUp/dbup-postgresql/actions/workflows/main.yml)                                                             | [![NuGet](https://img.shields.io/nuget/dt/dbup-postgresql.svg)](https://www.nuget.org/packages/dbup-postgresql)                             | [![NuGet](https://img.shields.io/nuget/v/dbup-postgresql.svg)](https://www.nuget.org/packages/dbup-postgresql)   | [![NuGet](https://img.shields.io/nuget/vpre/dbup-postgresql.svg)](https://www.nuget.org/packages/dbup-postgresql)   | [![view](https://img.shields.io/github/issues/DbUp/dbup-postgresql)](https://github.com/DbUp/dbup-postgresql)   | [![view](https://img.shields.io/github/issues-pr/DbUp/dbup-postgresql)](https://github.com/DbUp/dbup-postgresql)  |
| DbUp-Firebird    | [![GitHub Actions](https://img.shields.io/github/actions/workflow/status/DbUp/dbup-firebird/main.yml?branch=main)](https://github.com/DbUp/dbup-firebird/actions/workflows/main.ymlhttps://github.com/DbUp/dbup-firebird/actions/workflows/main.yml) | [![NuGet](https://img.shields.io/nuget/dt/dbup-firebird.svg)](https://www.nuget.org/packages/dbup-firebird)                                 | [![NuGet](https://img.shields.io/nuget/v/dbup-firebird.svg)](https://www.nuget.org/packages/dbup-firebird)       | [![NuGet](https://img.shields.io/nuget/vpre/dbup-firebird.svg)](https://www.nuget.org/packages/dbup-firebird)       | [![view](https://img.shields.io/github/issues/DbUp/dbup-firebird)](https://github.com/DbUp/dbup-firebird)       | [![view](https://img.shields.io/github/issues-pr/DbUp/dbup-firebird)](https://github.com/DbUp/dbup-firebird)      |
| DbUp-Oracle      | [![GitHub Actions](https://img.shields.io/github/actions/workflow/status/DbUp/dbup-oracle/main.yml?branch=main)](https://github.com/DbUp/dbup-oracle/actions/workflows/main.yml)                                                                     | [![NuGet](https://img.shields.io/nuget/dt/dbup-oracle.svg)](https://www.nuget.org/packages/dbup-oracle)                                     | [![NuGet](https://img.shields.io/nuget/v/dbup-oracle.svg)](https://www.nuget.org/packages/dbup-oracle)           | [![NuGet](https://img.shields.io/nuget/vpre/dbup-oracle.svg)](https://www.nuget.org/packages/dbup-oracle)           | [![view](https://img.shields.io/github/issues/DbUp/dbup-oracle)](https://github.com/DbUp/dbup-oracle)           | [![view](https://img.shields.io/github/issues-pr/DbUp/dbup-oracle)](https://github.com/DbUp/dbup-oracle)          |
| DbUp-Redshift    | [![GitHub Actions](https://img.shields.io/github/actions/workflow/status/DbUp/dbup-redshift/main.yml?branch=main)](https://github.com/DbUp/dbup-redshift/actions/workflows/main.yml)                                                                 | [![NuGet](https://img.shields.io/nuget/dt/dbup-redshift.svg)](https://www.nuget.org/packages/dbup-redshift)                                 | [![NuGet](https://img.shields.io/nuget/v/dbup-redshift.svg)](https://www.nuget.org/packages/dbup-redshift)       | [![NuGet](https://img.shields.io/nuget/vpre/dbup-redshift.svg)](https://www.nuget.org/packages/dbup-redshift)       | [![view](https://img.shields.io/github/issues/DbUp/dbup-redshift)](https://github.com/DbUp/dbup-redshift)       | [![view](https://img.shields.io/github/issues-pr/DbUp/dbup-redshift)](https://github.com/DbUp/dbup-redshift)      |

# End of Life Providers

The following providers are End of Life (EOL) and are no longer maintained:
- Sql Anywhere
- SqlCE
- SQLite (Mono)

# Extensions by the community

Maintenance and support for the extensions where not provided by the DbUp project. For questions and support on
these extensions, please contact the project directly.

## DbUpX

[https://github.com/fiscaltec/DbUpX](https://github.com/fiscaltec/DbUpX)

Extensions to DbUp supporting easy filtering, ordering and versioning:

- a journaling system that stores hashes of script contents, so we know if they need to rerun,
- a concept of "dependency comments" in scripts that let you more easily control the ordering of scripts,
- protection against code reorganisation affecting long script names,
- utilities for sorting and filtering scripts in helpful ways.

# Contributing

## NuGet Feed

To build the providers, you will need to add the DbUp NuGet feed to your local machine. Do this by generating
a GitHub token with `read:package` access and running:

```
dotnet nuget add source --name DbUp --username <YourUsername> --password <TheToken> https://nuget.pkg.github.com/DbUp/index.json
```
