# Awesome Database Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Community driven list of database tools

Here we will collect information about awesome useful and awesome experimental tools that simplify working with databases for DBA, DevOps, Developers and mere mortals.

Feel free to add information about your own db-tools or your favorite third-party db-tools.

For updates on `awesome-db-tools` and thoughts/news about databases/tools/SQL follow me at [@GraminMaksim](https://twitter.com/GraminMaksim)

## Contents
- [IDE](#ide)
- [GUI Managers/Clients](#gui-managersclients)
- [CLI tools](#cli-tools)
- [DB-schema navigation and visualization](#db-schema-navigation-and-visualization)
- [Modelers](#modelers)
- [Migration tools](#migration-tools)
- [Code generation tools](#code-generation-tools)
- [Wrappers](#wrappers)
- [Backup/Cloning tools](#backupcloning-tools)
- [Replication/Data operation](#replicationdata-operation)
- [Scripts](#scripts)
- [Monitoring/Statistics/Perfomance](#monitoringstatisticsperfomance)
  - [Prometheus](#prometheus)
  - [Zabbix](#zabbix)
- [Testing](#testing)
  - [Data generator](#data-generator)
- [Administration](#administration)
- [HA/Failover/Sharding](#hafailoversharding)
- [Kubernetes](#kubernetes)
- [Configuration Tuning](#configuration-tuning)
- [DevOps](#devops)
- [Schema samples](#schema-samples)
- [Reporting](#reporting)
- [Distributions](#distributions)
- [Security](#security)
- [SQL](#sql)
  - [Analyzers](#analyzers)
  - [Extensions](#extensions)
  - [Frameworks](#frameworks)
  - [Formatters](#formatters)
  - [Parsers](#parsers)
  - [Über SQL](#über-sql)
  - [Language Server Protocol](#language-server-protocol)
- [Papers](#papers)

## IDE
- [AnySQL Maestro](https://www.sqlmaestro.com/products/anysql/maestro) - Premier multi-purpose admin tool for database management, control and development.
- [Aqua Data Studio](https://www.aquafold.com/aquadatastudio) - Aqua Data Studio is productivity software for Database Developers, DBAs, and Analysts.
- [Database .net](http://fishcodelib.com/Database.htm) - Multiple database management tool with support for 20+ databases.
- [DataGrip](https://www.jetbrains.com/datagrip) - Cross-Platform IDE for Databases & SQL by JetBrains.
- [DataStation](https://github.com/multiprocessio/datastation) - Easily query, script, and visualize data from every database, file, and API.
- [DBeaver](https://github.com/dbeaver/dbeaver) - Free universal database manager and SQL client.
- [dbForge Studio for MySQL](https://www.devart.com/dbforge/mysql/studio) - Universal IDE for MySQL and MariaDB database development, management, and administration.
- [dbForge Studio for Oracle](https://www.devart.com/dbforge/oracle/studio) - Powerful IDE for Oracle management, administration, and development.
- [dbForge Studio for PostgreSQL](https://www.devart.com/dbforge/postgresql/studio) - GUI tool for managing and developing databases and objects.
- [dbForge Studio for SQL Server](https://www.devart.com/dbforge/sql/studio) - Powerful integrated development environment for SQL Server development, management, administration, data analysis, and reporting.
- [dbKoda](https://github.com/SouthbankSoftware/dbkoda) - Modern (JavaScript/Electron framework), open source IDE for MongoDB. It has features to support development, administration and performance tuning on MongoDB databases.
- [IBExpert](http://www.ibexpert.net/ibe) - Comprehensive GUI tool for Firebird and InterBase.
- [HeidiSQL](https://github.com/HeidiSQL/HeidiSQL) - A lightweight client for managing MySQL, MSSQL and PostgreSQL, written in Delphi.
- [MySQL Workbench](https://www.mysql.com/products/workbench) - MySQL Workbench is a unified visual tool for database architects, developers, and DBAs.
- [Navicat](https://www.navicat.com/en/products#navicat) - A database development tool that allows you to simultaneously connect to MySQL, MariaDB, SQL Server, Oracle, PostgreSQL, and SQLite databases from a single application.
- [Oracle SQL Developer](http://www.oracle.com/technetwork/developer-tools/sql-developer) - Oracle SQL Developer is a free, integrated development environment that simplifies the development and management of Oracle Database in both traditional and Cloud deployments.
- [pgAdmin](https://www.pgadmin.org) - The most popular and feature rich Open Source administration and development platform for PostgreSQL, the most advanced Open Source database in the world.
- [pgAdmin3](https://www.bigsql.org/pgadmin3) - Long Term Support for pgAdmin3.
- [PL/SQL Developer](https://www.allroundautomations.com/products/pl-sql-developer) - IDE that is specifically targeted at the development of stored program units for Oracle Databases.
- [PostgreSQL Maestro](https://www.sqlmaestro.com/products/postgresql/maestro) - Complete and powerful database management, admin and development tool for PostgreSQL.
- [Slashbase](https://github.com/slashbase/slashbase) - The open-source collaborative IDE for your databases. Connect to your database, browse data, run a bunch of SQL commands or share SQL queries with your team, right from your browser.
- [Toad](https://www.quest.com/toad/) - Toad is the premier database solution for developers, admins and data analysts. Manage complex database changes with a single database management tool.
- [Toad Edge](https://www.toadworld.com/products/toad-edge) - Simplified database development tool for MySQL and Postgres.
- [TOra](https://github.com/tora-tool/tora) - TOra is an open source SQL IDE for Oracle, MySQL and PostgreSQL dbs.
- [Valentina Studio](https://www.valentina-db.com/en/valentina-studio-overview) - Create, administer, query and explore Valentina DB, MySQL, MariaDB, PostgreSQL and SQLite databases for FREE.


## GUI Managers/Clients
- [Adminer](https://github.com/vrana/adminer) - Database management in a single PHP file.
- [Beekeeper Studio](https://github.com/beekeeper-studio/beekeeper-studio) - Open Source SQL Editor and Database Manager with a privacy commitment in their mission statement.
- [DbGate](https://github.com/dbgate/dbgate) - Database manager for MySQL, PostgreSQL, SQL Server, MongoDB, SQLite and others. Runs under Windows, Linux, Mac or as web application.
- [DbVisualizer](https://www.dbvis.com) - Universal database tool for developers, DBAs and analysts.
- [HouseOps](https://github.com/HouseOps/HouseOps) - Enterprise ClickHouse Ops UI for you run querys, monitoring ClickHouse health and make a lot of others thinks.
- [JackDB](https://www.jackdb.com) - Direct SQL access to all your data, no matter where it lives.
- [Jailer](https://github.com/Wisser/Jailer) - Database Subsetting and Relational Data Browsing Tool/Client.
- [MissionKontrol](https://www.missionkontrol.io) - Modern drag & drop admin panel/client with full user permissions for non-technical users.
- [ocelotgui](https://github.com/ocelot-inc/ocelotgui) - For MySQL, MariaDB, and Tarantool. Developed for Linux but can run on Windows.
- [OmniDB](https://github.com/OmniDB/OmniDB) - Web tool for database management.
- [Pgweb](https://github.com/sosedoff/pgweb) - Web-based database browser for PostgreSQL, written in Go and works on macOS, Linux and Windows machines.
- [phpLiteAdmin](https://www.phpliteadmin.org) - Web-based SQLite database admin tool written in PHP with support for SQLite3 and SQLite2.
- [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) - A web interface for MySQL and MariaDB.
- [psequel](http://www.psequel.com) - PSequel provides a clean and simple interface for you to perform common PostgreSQL tasks quickly.
- [PopSQL](https://popsql.com) - Modern, collaborative SQL editor for your team.
- [Postico](https://eggerapps.at/postico) - A Modern PostgreSQL Client for the Mac.
- [Robo 3T](https://github.com/Studio3T/robomongo) - Robo 3T (formerly Robomongo) is a shell-centric cross-platform MongoDB management tool.
- [Sequel Pro](https://github.com/sequelpro/sequelpro) - Sequel Pro is a fast, easy-to-use Mac database management application for working with MySQL & MariaDB databases.
- [SQL Operations Studio](https://github.com/microsoft/sqlopsstudio) - A data management tool that enables working with SQL Server, Azure SQL DB and SQL DW from Windows, macOS and Linux.
- [SQLite Expert](http://www.sqliteexpert.com/index.html) - Graphical interface supports all SQLite features.
- [sqlite-tui](https://github.com/mathaou/sqlite-tui) - A TUI for viewing sqlite databases, written in Go.
- [sqlpad](https://github.com/rickbergfalk/sqlpad) - Web-based SQL editor run in your own private cloud.
- [SQLPro](https://www.macpostgresclient.com) - A simple, powerful Postgres manager for macOS.
- [SQuirreL](https://sourceforge.net/projects/squirrel-sql) - Graphical SQL client written in Java that will allow you to view the structure of a JDBC compliant database, browse the data in tables, issue SQL commands etc.
- [SQLTools](https://github.com/mtxr/vscode-sqltools) - Database management for VSCode.
- [SQLyog](https://www.webyog.com/product/sqlyog) - The most complete and easy to use MySQL GUI.
- [Tabix](https://github.com/tabixio/tabix) - SQL Editor & Open source simple business intelligence for Clickhouse.
- [TablePlus](https://github.com/TablePlus/TablePlus) - Modern, native, and friendly GUI tool for relational databases: MySQL, PostgreSQL, SQLite & more.
- [TeamPostgreSQL](http://www.teampostgresql.com) - PostgreSQL Web Administration GUI - use your PostgreSQL databases from anywhere, with rich, lightning-fast AJAX web interface.


## CLI tools
- [ipython-sql](https://github.com/catherinedevlin/ipython-sql) - Connect to a database for issue SQL commands within IPython or IPython Notebook.
- [iredis](https://github.com/laixintao/iredis) - A Cli for Redis with AutoCompletion and Syntax Highlighting.
- [pgcenter](https://github.com/lesovsky/pgcenter) - Top-like admin tool for PostgreSQL.
- [pg_activity](https://github.com/julmon/pg_activity) - Top like application for PostgreSQL server activity monitoring.
- [pg_top](https://github.com/markwkm/pg_top) - 'top' for PostgreSQL.
- [pspg](https://github.com/okbob/pspg) - Postgres Pager.
- [SQLcl](http://www.oracle.com/technetwork/developer-tools/sqlcl/overview/index.html) - Oracle SQL Developer Command Line (SQLcl) is a free command line interface for Oracle Database.
- [SQLLine](https://github.com/julianhyde/sqlline) - Command-line shell for issuing SQL to relational databases via JDBC.
- [usql](https://github.com/xo/usql) - A universal command-line interface for PostgreSQL, MySQL, Oracle Database, SQLite3, Microsoft SQL Server, and many other databases including NoSQL and non-relational databases!

### dbcli
- [athenacli](https://github.com/dbcli/athenacli) - AthenaCLI is a CLI tool for AWS Athena service that can do auto-completion and syntax highlighting.
- [litecli](https://github.com/dbcli/litecli) - CLI for SQLite Databases with auto-completion and syntax highlighting.
- [mssql-cli](https://github.com/dbcli/mssql-cli) - A command-line client for SQL Server with auto-completion and syntax highlighting.
- [mycli](https://github.com/dbcli/mycli) - A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting.
- [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting.
- [vcli](https://github.com/dbcli/vcli) - Vertica CLI with auto-completion and syntax highlighting.


## DB-schema navigation and visualization
- [dbdiagram.io](https://dbdiagram.io) - Quick and simple tool for help you draw your database relationship diagrams and flow quickly using simple DSL language.
- [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - Entity Relation Diagrams generation tool.
- [SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler) - A free database schema discovery and comprehension tool.
- [Schema Spy](https://github.com/schemaspy/schemaspy) - Generating your database to HTML documentation, including Entity Relationship diagrams.
- [tbls](https://github.com/k1LoW/tbls) - CI-Friendly tool for document a database, written in Go.


## Modelers
- [ERBuilder Data Modeler](https://soft-builder.com/erbuilder-data-modeler) - Easy-to-use database modeling software for high-quality data models. It's a complete data modeling solution for data modelers and data architects.
- [Navicat Data Modeler](https://www.navicat.com/en/products/navicat-data-modeler) - A powerful and cost-effective database design tool which helps you build high-quality conceptual, logical and physical data models.
- [Oracle SQL Developer Data Modeler](http://www.oracle.com/technetwork/developer-tools/datamodeler/overview/index.html) - Oracle SQL Developer Data Modeler is a free graphical tool that enhances productivity and simplifies data modeling tasks.
- [pgmodeler](https://github.com/pgmodeler/pgmodeler) - Data modeling tool designed for PostgreSQL.


## Migration tools
- [2bass](https://github.com/CourseOrchestra/2bass) - Database configuration-as-code tool that utilizes concept of idempotent DDL scripts.
- [Bytebase](https://github.com/bytebase/bytebase) - Web-based, zero-config, dependency-free database schema change and version control tool for teams.
- [flyway](https://github.com/flyway/flyway) - Database migration tool.
- [gh-ost](https://github.com/github/gh-ost) - Online schema migration for MySQL.
- [liquibase](https://github.com/liquibase/liquibase) - Database-independent library for tracking, managing and applying database schema changes.
- [migra](https://github.com/djrobstep/migra) - Like diff but for PostgreSQL schemas.
- [node-pg-migrate](https://github.com/salsita/node-pg-migrate) - Node.js database migration management built exclusively for postgres. (But can also be used for other DBs conforming to SQL standard - e.g. CockroachDB.)
- [Prisma Migrate](https://github.com/prisma/migrate) - Declarative database schema migration tool that uses a declarative data modeling syntax to describe your database schema.
- [Pyrseas](https://github.com/perseas/Pyrseas) - Provides utilities to describe a PostgreSQL database schema as YAML.
- [SchemaHero](https://github.com/schemahero/schemahero) - A Kubernetes operator for declarative database schema management (gitops for database schemas).
- [Sqitch](https://github.com/sqitchers/sqitch) - Sensible database-native change management for framework-free development and dependable deployment.
- [yuniql](https://github.com/rdagumampan/yuniql) - Yet another schema versioning and migration tool just made with native .NET Core 3.0+ and hopefully better.


## Code generation tools
- [ddl-generator](https://github.com/catherinedevlin/ddl-generator) - Infers SQL DDL (Data Definition Language) from table data.
- [scheme2ddl](https://github.com/qwazer/scheme2ddl) - Command line util for export Oracle schema to set of ddl init scripts with ability to filter undesirable information, separate DDL in different files, pretty format output.


## Wrappers
- [DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory) - A open source REST API backend for mobile, web, and IoT applications.
- [FBSQL Frontend Backend SQL](https://github.com/fbsql/fbsql) - Work (secure) with your backend database within HTML.
- [Hasura GraphQL Engine](https://github.com/hasura/graphql-engine) - Blazing fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events.
- [jl-sql](https://github.com/avz/jl-sql) - SQL for JSON and CSV streams.
- [mysql_fdw](https://github.com/EnterpriseDB/mysql_fdw) - PostgreSQL foreign data wrapper for MySQL.
- [Oracle REST Data Services](http://www.oracle.com/technetwork/developer-tools/rest-data-services) - A mid-tier Java application, ORDS maps HTTP(S) verbs (GET, POST, PUT, DELETE, etc.) to database transactions and returns any results formatted using JSON.
- [Prisma](https://github.com/prismagraphql/prisma) -  Prisma turns your database into a realtime GraphQL API.
- [PostgREST](https://github.com/PostgREST/postgrest) - REST API for any Postgres database.
- [prest](https://github.com/prest/prest) - Is a way to serve a RESTful API from any databases written in Go.
- [restSQL](https://github.com/restsql/restsql) - SQL generator with Java and HTTP APIs, uses a simple RESTful HTTP API with XML or JSON serialization.
- [resquel](https://github.com/formio/resquel) - Easily convert your SQL database into a REST API.
- [Saltcorn](https://github.com/saltcorn/saltcorn) - Open source no-code builder for web datatabase applications. Server and drag-and-drop UI builder, data stored in PostgreSQL or SQLite.
- [sandman2](https://github.com/jeffknupp/sandman2) - Automatically generate a RESTful API service for your legacy database.


## Backup/Cloning tools
- [Database Lab Engine](https://gitlab.com/postgres-ai/database-lab) - Instant thin cloning for Postgres to scale the development process.
- [BaRMan](https://github.com/2ndquadrant-it/barman) - Backup and Recovery Manager for PostgreSQL.
- [pgbackrest](https://github.com/pgbackrest/pgbackrest) - Reliable PostgreSQL Backup & Restore.


## Replication/Data operation
- [Datasette](https://github.com/simonw/datasette) - A tool for exploring and publishing data.
- [dtle](https://github.com/actiontech/dtle) - Distributed Data Transfer Service for MySQL.
- [Litestream](https://github.com/benbjohnson/litestream) - Streaming replication for SQLite.
- [pgsync](https://github.com/ankane/pgsync) - Sync Postgres data between databases.
- [pg_chameleon](https://github.com/the4thdoctor/pg_chameleon) - MySQL to PostgreSQL replica system written in Python 3. The system use the library mysql-replication to pull the row images from MySQL which are stored into PostgreSQL as JSONB.
- [PGDeltaStream](https://github.com/hasura/pgdeltastream) - A Golang webserver to stream Postgres changes atleast-once over websockets, using Postgres logical decoding feature.
- [repmgr](https://github.com/2ndQuadrant/repmgr) - The Most Popular Replication Manager for PostgreSQL.


## Scripts
- [DBA MultiTool](https://github.com/LowlyDBA/dba-multitool) - T-SQL scripts for the long haul: optimizing storage, on-the-fly documentation, and general administrative needs for SQL Server.
- [pgx_scripts](https://github.com/pgexperts/pgx_scripts) - A collection of useful little scripts for database analysis and administration, created by our team at PostgreSQL Experts.
- [pgsql-bloat-estimation](https://github.com/ioguix/pgsql-bloat-estimation) - Queries to mesure statistical bloat in indexes and tables for PostgreSQL.
- [pgWikiDont](https://gitlab.com/depesz/pgWikiDont) - SQL test that checks if your database follows rules from <https://wiki.postgresql.org/wiki/Don't_Do_This>.
- [pg-utils](https://github.com/dataegret/pg-utils) - Useful PostgreSQL utilities.
- [Postgres cheat sheet](https://postgrescheatsheet.com) - Useful SQL-scripts and commands by <timescale.com>.
- [postgres_dba](https://github.com/NikolayS/postgres_dba) - The missing set of useful tools for Postgres DBAs and all engineers.
- [postgres_queries_and_commands.sql](https://gist.github.com/rgreenjr/3637525) - Useful PostgreSQL Queries and Commands.
- [TPT](https://github.com/tanelpoder/tpt-oracle) - These sqlplus scripts are for Oracle Database performance optimization & troubleshooting.


## Monitoring/Statistics/Perfomance
- [ASH Viewer](https://github.com/akardapolov/ASH-Viewer) - Provides a graphical view of active session history data within the Oracle and PostgreSQL DB.
- [Monyog](https://www.webyog.com/product/monyog) - Agentless & Cost-effective MySQL Monitoring Tool.
- [mssql-monitoring](https://github.com/microsoft/mssql-monitoring) - Monitor your SQL Server on Linux performance using collectd, InfluxDB and Grafana.
- [Navicat Monitor](https://www.navicat.com/en/products/navicat-monitor) - A safe, simple and agentless remote server monitoring tool that is packed with powerful features to make your monitoring effective as possible.
- [Percona Monitoring and Management](https://github.com/percona/pmm) - Open source platform for managing and monitoring MySQL and MongoDB performance.
- [pganalyze collector](https://github.com/pganalyze/collector) - Pganalyze statistics collector for gathering PostgreSQL metrics and log data.
- [postgres-checkup](https://gitlab.com/postgres-ai/postgres-checkup) - New-generation diagnostics tool that allows users to do a deep analysis of the health of Postgres databases.
- [pgDash](https://pgdash.io) - Measure and track every aspect of your PostgreSQL databases.
- [PgHero](https://github.com/ankane/pghero) - A performance dashboard for Postgres - health checks, suggested indexes, and more.
- [pgmetrics](https://github.com/rapidloop/pgmetrics) - Collect and display information and stats from a running PostgreSQL server.
- [pgMustard](https://www.pgmustard.com) - A user interface for Postgres explain plans, plus tips to improve performance.
- [pgstats](https://github.com/gleu/pgstats) - Collects PostgreSQL statistics, and either saves them in CSV files or print them on the stdout.
- [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) - Flexible self-contained PostgreSQL metrics monitoring/dashboarding solution.
- [Telegraf PostgreSQL plugin](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/postgresql) - Provides metrics for your postgres database.

### Prometheus
- [pgSCV](https://github.com/weaponry/pgscv) - Metrics exporter for PostgreSQL and Postgres-related services.
- [postgres_exporter](https://github.com/wrouesnel/postgres_exporter) - Prometheus exporter for PostgreSQL server metrics.

### Zabbix
- [Mamonsu](https://github.com/postgrespro/mamonsu) - Monitoring agent for PostgreSQL.
- [Orabbix](http://www.smartmarmot.com/wiki/index.php?title=Orabbix) - Orabbix is a plugin designed to work with Zabbix Enterprise Monitor to provide multi-tiered monitoring, performance and availability reporting and measurement for Oracle Databases, along with server performance metrics.
- [pg_monz](https://github.com/pg-monz/pg_monz) - This is the Zabbix monitoring template for PostgreSQL Database.
- [Pyora](https://github.com/bicofino/Pyora) - Python script to monitor Oracle Databases.
- [ZabbixDBA](https://github.com/anetrusov/ZabbixDBA) - ZabbixDBA is fast, flexible, and continuously developing plugin to monitor your RDBMS.


## Testing
- [DbFit](https://github.com/dbfit/dbfit) - A database testing framework that supports easy test-driven development of your database code.
- [RegreSQL](https://github.com/dimitri/regresql) - Regression Testing your SQL queries.


### Data generator
- [Databene Benerator](https://sourceforge.net/projects/benerator) - It is a framework for generating realistic and valid high-volume test data for your system under test (avoiding the Datalite anti-pattern).
- [dbForge Data Generator for MySQL](https://www.devart.com/dbforge/mysql/data-generator) - Powerful GUI tool for creating massive volumes of realistic test data.
- [dbForge Data Generator for Oracle](https://www.devart.com/dbforge/oracle/data-generator) - Small but mighty GUI tool for populating Oracle schemas with tons of realistic test data.
- [dbForge Data Generator for SQL Server](https://www.devart.com/dbforge/sql/data-generator) - Powerful GUI tool for a fast generation of meaningful test data for databases.
- [Noisia](https://github.com/lesovsky/noisia) - Harmful workload generator for PostgreSQL.
- [SB Data Generator](https://soft-builder.com/sb-data-generator) - Simple and powerful tool to generate and populate selected tables or entire databases with realistic test data for your applications. Generate test data for: Oracle, MS SQL Server, MySQL, PostgreSQL, Firebird, SQLite, Azure SQL Database, Amazon Redshift and Amazon RDS.

## Administration
- [pgbadger](https://github.com/dalibo/pgbadger) - A fast PostgreSQL Log Analyzer.
- [pgbedrock](https://github.com/Squarespace/pgbedrock) - Manage a Postgres cluster's roles, role memberships, schema ownership, and privileges.
- [pgslice](https://github.com/ankane/pgslice) - Postgres partitioning as easy as pie.


## HA/Failover/Sharding
- [Citus](https://github.com/citusdata/citus) - Postgres extension that distributes your data and your queries across multiple nodes.
- [patroni](https://github.com/zalando/patroni) - A template for PostgreSQL High Availability with ZooKeeper, etcd, or Consul.
- [Percona XtraDB Cluster](https://github.com/percona/percona-xtradb-cluster) - A High Scalability Solution for MySQL Clustering and High Availability.
- [stolon](https://github.com/sorintlab/stolon) - Cloud native PostgreSQL manager for PostgreSQL high availability.
- [pg_auto_failover](https://github.com/citusdata/pg_auto_failover) - Postgres extension and service for automated failover and high-availability.
- [pglookout](https://github.com/aiven/pglookout) - PostgreSQL replication monitoring and failover daemon.
- [PostgreSQL Automatic Failover](https://github.com/ClusterLabs/PAF) - High-Availibility for Postgres, based on industry references Pacemaker and Corosync.
- [postgresql_cluster](https://github.com/vitabaks/postgresql_cluster) - PostgreSQL High-Availability Cluster (based on "Patroni" and "DCS(etcd)"). Automating deployment with Ansible.
- [Vitess](https://github.com/vitessio/vitess) - Database clustering system for horizontal scaling of MySQL through generalized sharding.


## Kubernetes
- [KubeDB](https://kubedb.com) - Making running production-grade databases easy on Kubernetes.
- [Postgres operator](https://github.com/zalando/postgres-operator) - The Postgres Operator enables highly-available PostgreSQL clusters on Kubernetes (K8s) powered by Patroni.
- [Spilo](https://github.com/zalando/spilo) - HA PostgreSQL Clusters with Docker.
- [StackGres](https://gitlab.com/ongresinc/stackgres) - Enterprise-grade, Full Stack PostgreSQL on Kubernetes.


## Configuration Tuning
- [MySQLTuner-perl](https://github.com/major/MySQLTuner-perl) - Script written in Perl that allows you to review a MySQL installation quickly and make adjustments to increase performance and stability.
- [PGConfigurator](https://pgconfigurator.cybertec-postgresql.com) - Free online tool to generate an optimized `postgresql.conf`.
- [pgtune](https://github.com/gregs1104/pgtune) - PostgreSQL configuration wizard.
- [postgresqltuner.pl](https://github.com/jfcoz/postgresqltuner) - Simple script to analyse your PostgreSQL database configuration, and give tuning advice.


## DevOps
- [DBmaestro](https://www.dbmaestro.com) - DBmaestro accelerates release cycles & supports agility across the entire IT ecosystem.
- [Spawn](https://spawn.cc/) - Cloud service for creating instant database copies for development and CI. No more local db installs, instant recovery to arbitrary save points, isolated copies for each feature branch or test. Instant provisioning regardless of database size.
- [Toad DevOps Toolkit](https://www.quest.com/products/toad-devops-toolkit/) - Toad DevOps Toolkit executes key database development functions within your DevOps workflow —without compromising quality, performance or reliability.


## Schema samples
- [Oracle Database Sample Schemas](https://github.com/oracle/db-sample-schemas) - Oracle Database Sample Schemas.


## Reporting
- [Chartbrew](https://chartbrew.com) - Create live dashboards, charts, and client reports from multiple databases and services.
- [Poli](https://github.com/shzlw/poli) - An easy-to-use SQL reporting application built for SQL lovers.


## Distributions
- [DBdeployer](https://github.com/datacharmer/dbdeployer) - Tool that deploys MySQL database servers easily.
- [dbatools](https://github.com/sqlcollaborative/dbatools) - PowerShell module that you may think of like a command-line SQL Server Management Studio.
- [Postgres.app](https://github.com/PostgresApp/PostgresApp) - Full-featured PostgreSQL installation packaged as a standard Mac app.
- [BigSQL](https://www.bigsql.org) - A developer-friendly distribution of Postgres.
- [Elephant Shed](https://github.com/credativ/elephant-shed) - Web-based PostgreSQL management front-end that bundles several utilities and applications for use with PostgreSQL.


## Security
- [Acra](https://github.com/cossacklabs/acra) - Database security suite. Database proxy with field-level encryption, search through encrypted data, SQL injections prevention, intrusion detection, honeypots. Supports client-side and proxy-side ("transparent") encryption. SQL, NoSQL.
- [Databunker](https://github.com/securitybunker/databunker) - Special GDPR compliant secure vault for customer records built on top of regular DB.
- [Inspektor](https://github.com/poonai/inspektor) - Access control layer for databases. Inspektor leverages open policy agent to make policy decisions.


## SQL

### Analyzers
- [SQLCheck](https://github.com/jarulraj/sqlcheck) - Automatically detects common SQL anti-patterns.
- [SQLFluff](https://github.com/sqlfluff/sqlfluff) - Dialect-flexible and configurable SQL linter.
- [TSQLLint](https://github.com/tsqllint/tsqllint) - A tool for describing, identifying, and reporting the presence of anti-patterns in TSQL scripts.

### Extensions
- [PartiQL](https://partiql.org) - SQL-compatible access to relational, semi-structured, and nested data.

### Frameworks
- [Apache Calcite](https://calcite.apache.org) - Dynamic data management framework with advanced SQL features.
- [ZetaSQL](https://github.com/google/zetasql) - Analyzer Framework for SQL.

### Formatters
- [CodeBuff](https://github.com/antlr/codebuff) - Language-agnostic pretty-printing through machine learning.
- [pgFormatter](https://github.com/darold/pgFormatter) - A PostgreSQL SQL syntax beautifier.
- [Poor SQL](https://poorsql.com) - Instant free and open-source T-SQL formatting. 
- [SQL Formatter](https://github.com/zeroturnaround/sql-formatter) - JavaScript library for pretty-printing SQL queries.

### Parsers
- [General SQL Parser](https://www.sqlparser.com) - Parsing, formatting, modification and analysis for SQL.
- [jOOQ](https://github.com/jOOQ/jOOQ) - Parses SQL, translates it to other dialects, and allows for expression tree transformations.
- [JSqlParser](https://github.com/JSQLParser/JSqlParser) - Parses an SQL statement and translate it into a hierarchy of Java classes.
- [More SQL Parsing!](https://github.com/klahnakoski/mo-sql-parsing) - Parse SQL into JSON.
- [sqlparse](https://github.com/andialbrecht/sqlparse) - Non-validating SQL parser for Python.

### Über SQL
Running SQL queries against various databases, structured text, etc.
- [csvq](https://github.com/mithrandie/csvq) - SQL-like query language for CSV.
- [dsq](https://github.com/multiprocessio/dsq) - Commandline tool for running SQL queries against JSON, CSV, Excel, Parquet, and more.
- [OctoSQL](https://github.com/cube2222/octosql) - Query tool that allows you to join, analyse and transform data from multiple databases and file formats using SQL.
- [TextQL](https://github.com/dinedal/textql) - Execute SQL against structured text like CSV or TSV.
- [trdsql](https://github.com/noborus/trdsql) - CLI tool that can execute SQL queries on CSV, LTSV, JSON and TBLN.

### Language Server Protocol
- [SQLLanguageServer](https://github.com/joe-re/sql-language-server) - SQL Language Server.
- [sqls](https://github.com/lighttiger2505/sqls) - SQL Language Server written in Go.


## Papers
Documents, articles, manifestos and other theoretical materials on database tools
- [The "Database as Code" Manifesto](https://github.com/mgramin/database-as-code) - Treat your database as Code.


## Contributing
- Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.
