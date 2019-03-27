# Awesome Database Tools [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> Community driven list of database tools

Here we will collect information about awesome useful and awesome experimental database tools for DBA, DevOps, Developers and mere mortals.

Feel free to add information about your own db-tools or your favorite third-party db-tools.

## Contents

- [IDE](#ide)
- [GUI Managers/Clients](#gui-managersclients)
- [CLI tools](#cli-tools)
- [DB-schema navigation and visualization](#db-schema-navigation-and-visualization)
- [Modelers](#modelers)
- [Migration tools](#migration-tools)
- [Code generation tools](#code_generation_tools)
- [HTTP wrappers](#http-wrappers)
- [Backup tools](#backup-tools)
- [Replication](#replication)
- [Scripts](#scripts)
- [Monitoring/Statistics/Perfomance](#monitoringstatisticsperfomance)
  - [Zabbix](#zabbix)
- [Testing](#testing)
  - [Data generator](#data-generator)
- [Administration](#administration)
- [DevOps](#devops)
- [Schema samples](#schema-samples)
- [Contributing](#contributing)
- [License](#license)


### IDE
- [Aqua Data Studio](https://www.aquafold.com/aquadatastudio) - Aqua Data Studio is productivity software for Database Developers, DBAs, and Analysts.
- [Database .net](http://fishcodelib.com/Database.htm) - Multiple database management tool with support for 20+ databases.
- [DataGrip](https://www.jetbrains.com/datagrip) - Cross-Platform IDE for Databases & SQL by JetBrains.
- [DBeaver](https://github.com/dbeaver/dbeaver) - Free universal database manager and SQL client.
- [dbForge Studio for MySQL](https://www.devart.com/dbforge/mysql/studio) - Universal IDE for MySQL and MariaDB database development, management, and administration.
- [dbForge Studio for Oracle](https://www.devart.com/dbforge/oracle/studio) - Powerful IDE for Oracle management, administration, and development.
- [dbForge Studio for PostgreSQL](https://www.devart.com/dbforge/postgresql/studio) - GUI tool for managing and developing databases and objects.
- [dbForge Studio for SQL Server](https://www.devart.com/dbforge/sql/studio) - Powerful integrated development environment for SQL Server development, management, administration, data analysis, and reporting.
- [HeidiSQL](https://github.com/HeidiSQL/HeidiSQL) - A lightweight client for managing MySQL, MSSQL and PostgreSQL, written in Delphi.
- [Navicat](https://www.navicat.com/en/products#navicat) - A database development tool that allows you to simultaneously connect to MySQL, MariaDB, SQL Server, Oracle, PostgreSQL, and SQLite databases from a single application.
- [Oracle SQL Developer](http://www.oracle.com/technetwork/developer-tools/sql-developer) - Oracle SQL Developer is a free, integrated development environment that simplifies the development and management of Oracle Database in both traditional and Cloud deployments.
- [pgAdmin](https://www.pgadmin.org) - The most popular and feature rich Open Source administration and development platform for PostgreSQL, the most advanced Open Source database in the world.
- [Toad](https://www.quest.com/toad/) - Toad is the premier database solution for developers, admins and data analysts. Manage complex database changes with a single database management tool.


### GUI Managers/Clients
- [Adminer](https://github.com/vrana/adminer) - Database management in a single PHP file.
- [HouseOps](https://github.com/HouseOps/HouseOps) - Enterprise ClickHouse Ops UI for you run querys, monitoring ClickHouse health and make a lot of others thinks.
- [OmniDB](https://github.com/OmniDB/OmniDB) - Web tool for database management.
- [Pgweb](https://github.com/sosedoff/pgweb) - Web-based database browser for PostgreSQL, written in Go and works on macOS, Linux and Windows machines.
- [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - A web interface for MySQL and MariaDB.
- [Postico](https://eggerapps.at/postico) - A Modern PostgreSQL Client for the Mac.
- [Robo 3T](https://github.com/Studio3T/robomongo) - Robo 3T (formerly Robomongo) is a shell-centric cross-platform MongoDB management tool.
- [SQL Operations Studio](https://github.com/microsoft/sqlopsstudio) - A data management tool that enables working with SQL Server, Azure SQL DB and SQL DW from Windows, macOS and Linux.
- [Tabix](https://github.com/tabixio/tabix) - SQL Editor & Open source simple business intelligence for Clickhouse.
- [TablePlus](https://github.com/TablePlus/TablePlus) - Modern, native, and friendly GUI tool for relational databases: MySQL, PostgreSQL, SQLite & more.


### CLI tools
- [ipython-sql](https://github.com/catherinedevlin/ipython-sql) - Connect to a database for issue SQL commands within IPython or IPython Notebook.
- [pgcenter](https://github.com/lesovsky/pgcenter) - Top-like admin tool for PostgreSQL.
- [pg_activity](https://github.com/julmon/pg_activity) - Top like application for PostgreSQL server activity monitoring.
- [pspg](https://github.com/okbob/pspg) - Postgres Pager.
- [SQLcl](http://www.oracle.com/technetwork/developer-tools/sqlcl/overview/index.html) - Oracle SQL Developer Command Line (SQLcl) is a free command line interface for Oracle Database.
- [usql](https://github.com/xo/usql) - A universal command-line interface for PostgreSQL, MySQL, Oracle Database, SQLite3, Microsoft SQL Server, [and many other databases](https://github.com/xo/usql#database-support) including NoSQL and non-relational databases!


### DB-schema navigation and visualization
- [dbdiagram.io](https://dbdiagram.io) - Quick and simple tool for help you draw your database relationship diagrams and flow quickly using simple DSL language.
- [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - Entity Relation Diagrams generation tool.
- [SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler) - A free database schema discovery and comprehension tool.
- [Schema Spy](https://github.com/schemaspy/schemaspy) - Generating your database to HTML documentation, including Entity Relationship diagrams.


### Modelers
- [Navicat Data Modeler](https://www.navicat.com/en/products/navicat-data-modeler) - A powerful and cost-effective database design tool which helps you build high-quality conceptual, logical and physical data models.
- [Oracle SQL Developer Data Modeler](http://www.oracle.com/technetwork/developer-tools/datamodeler/overview/index.html) - Oracle SQL Developer Data Modeler is a free graphical tool that enhances productivity and simplifies data modeling tasks.
- [pgmodeler](https://github.com/pgmodeler/pgmodeler) - Data modeling tool designed for PostgreSQL.


### Migration tools
- [2bass](https://github.com/CourseOrchestra/2bass) - Database configuration-as-code tool that utilizes concept of idempotent DDL scripts.
- [flyway](https://github.com/flyway/flyway) - Database migration tool.
- [gh-ost](https://github.com/github/gh-ost) - Online schema migration for MySQL.
- [liquibase](https://github.com/liquibase/liquibase) - Database-independent library for tracking, managing and applying database schema changes.
- [node-pg-migrate](https://github.com/salsita/node-pg-migrate) - Node.js database migration management built exclusively for postgres. (But can also be used for other DBs conforming to SQL standard - e.g. CockroachDB.)
- [Pyrseas](https://github.com/perseas/Pyrseas) - Provides utilities to describe a PostgreSQL database schema as YAML.


### Code generation tools
- [ddl-generator](https://github.com/catherinedevlin/ddl-generator) - Infers SQL DDL (Data Definition Language) from table data.
- [scheme2ddl](https://github.com/qwazer/scheme2ddl) - Command line util for export oracle schema to set of ddl scripts.


### HTTP wrappers
- [DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory) - A open source REST API backend for mobile, web, and IoT applications.
- [mysql_fdw](https://github.com/EnterpriseDB/mysql_fdw) - PostgreSQL foreign data wrapper for MySQL.
- [Oracle REST Data Services](http://www.oracle.com/technetwork/developer-tools/rest-data-services) - A mid-tier Java application, ORDS maps HTTP(S) verbs (GET, POST, PUT, DELETE, etc.) to database transactions and returns any results formatted using JSON.
- [Prisma](https://github.com/prismagraphql/prisma) -  Prisma turns your database into a realtime GraphQL API.
- [PostgREST](https://github.com/PostgREST/postgrest) - REST API for any Postgres database.
- [prest](https://github.com/prest/prest) - Is a way to serve a RESTful API from any databases written in Go.
- [restSQL](https://github.com/restsql/restsql) - Is a open-source, ultra-lightweight data access layer for HTTP clients.
- [resquel](https://github.com/formio/resquel) - Easily convert your SQL database into a REST API.


### Backup tools
- [pgbackrest](https://github.com/pgbackrest/pgbackrest) - Reliable PostgreSQL Backup & Restore.
- [BaRMan](https://github.com/2ndquadrant-it/barman) - Backup and Recovery Manager for PostgreSQL.


### Replication
- [pg_chameleon](https://github.com/the4thdoctor/pg_chameleon) - MySQL to PostgreSQL replica system written in Python 3. The system use the library mysql-replication to pull the row images from MySQL which are stored into PostgreSQL as JSONB.
- [PGDeltaStream](https://github.com/hasura/pgdeltastream) - A Golang webserver to stream Postgres changes atleast-once over websockets, using Postgres logical decoding feature.


### Scripts
- [pgx_scripts](https://github.com/pgexperts/pgx_scripts) - A collection of useful little scripts for database analysis and administration, created by our team at PostgreSQL Experts.
- [pgsql-bloat-estimation](https://github.com/ioguix/pgsql-bloat-estimation) - Queries to mesure statistical bloat in indexes and tables for PostgreSQL.
- [pg-utils](https://github.com/dataegret/pg-utils) - Useful PostgreSQL utilities.
- [postgres_dba](https://github.com/NikolayS/postgres_dba) - The missing set of useful tools for Postgres DBAs and all engineers.


### Monitoring/Statistics/Perfomance
- [Navicat Monitor](https://www.navicat.com/en/products/navicat-monitor) - A safe, simple and agentless remote server monitoring tool that is packed with powerful features to make your monitoring effective as possible.
- [pganalyze collector](https://github.com/pganalyze/collector) - Pganalyze statistics collector for gathering PostgreSQL metrics and log data.
- [pgDash](https://pgdash.io) - Measure and track every aspect of your PostgreSQL databases.
- [PgHero](https://github.com/ankane/pghero) - A performance dashboard for Postgres - health checks, suggested indexes, and more.
- [pgmetrics](https://github.com/rapidloop/pgmetrics) - Collect and display information and stats from a running PostgreSQL server.
- [pgstats](https://github.com/gleu/pgstats) - Collects PostgreSQL statistics, and either saves them in CSV files or print them on the stdout.
- [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) - Flexible self-contained PostgreSQL metrics monitoring/dashboarding solution.

#### Zabbix
- [Orabbix](http://www.smartmarmot.com/wiki/index.php?title=Orabbix) - Orabbix is a plugin designed to work with Zabbix Enterprise Monitor to provide multi-tiered monitoring, performance and availability reporting and measurement for Oracle Databases, along with server performance metrics.
- [ZabbixDBA](https://github.com/anetrusov/ZabbixDBA) - ZabbixDBA is fast, flexible, and continuously developing plugin to monitor your RDBMS.
- [Pyora](https://github.com/bicofino/Pyora) - Python script to monitor Oracle Databases.


### Testing
- [DbFit](https://github.com/dbfit/dbfit) - A database testing framework that supports easy test-driven development of your database code.

#### Data generator
- [Databene Benerator](https://sourceforge.net/projects/benerator) - It is a framework for generating realistic and valid high-volume test data for your system under test (avoiding the Datalite anti-pattern).
- [dbForge Data Generator for MySQL](https://www.devart.com/dbforge/mysql/data-generator) - Powerful GUI tool for creating massive volumes of realistic test data.
- [dbForge Data Generator for Oracle](https://www.devart.com/dbforge/oracle/data-generator) - Small but mighty GUI tool for populating Oracle schemas with tons of realistic test data.
- [dbForge Data Generator for SQL Server](https://www.devart.com/dbforge/sql/data-generator) - Powerful GUI tool for a fast generation of meaningful test data for databases.


### Administration
- [patroni](https://github.com/zalando/patroni) - A template for PostgreSQL High Availability with ZooKeeper, etcd, or Consul.
- [pgbadger](https://github.com/dalibo/pgbadger) - A fast PostgreSQL Log Analyzer.
- [pgtune](https://github.com/gregs1104/pgtune) - PostgreSQL configuration wizard.


### DevOps
- [DBmaestro](https://www.dbmaestro.com) - DBmaestro accelerates release cycles & supports agility across the entire IT ecosystem.
- [Toad DevOps Toolkit](https://www.quest.com/products/toad-devops-toolkit/) - Toad DevOps Toolkit executes key database development functions within your DevOps workflow —without compromising quality, performance or reliability.


### Schema samples
- [Oracle Database Sample Schemas](https://github.com/oracle/db-sample-schemas) - Oracle Database Sample Schemas.


## Contributing
- Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
