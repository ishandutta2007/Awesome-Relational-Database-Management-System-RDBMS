# Awesome-Relational-Database-Management-System-RDBMS

## Top Relational Database Management System (RDBMS) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on SQL Databases, Cloud-Managed Engines & Open-Source RDBMS Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial RDBMS platforms** and **open-source projects** that store, query, and manage structured data using SQL. These databases power everything from embedded mobile apps to petabyte-scale cloud data warehouses.



**Examples** include Microsoft SQL Server, Oracle Database, PostgreSQL, MySQL, IBM Db2, MariaDB, SQLite, Amazon Aurora, Google Cloud SQL, and SAP ASE (the category leaders).



**Open-source emphasis**: RDBMS is one of the strongest open-source domains. **PostgreSQL** and **MySQL** collectively power the majority of web applications, with **MariaDB** as the community-driven MySQL fork, **SQLite** as the embedded standard, and **CockroachDB**, **YugabyteDB**, and **TiDB** bringing distributed SQL to open source. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/)**  

  Microsoft's enterprise RDBMS with T-SQL, strong Windows integration, and Azure SQL Database as the cloud-managed option. **The standard for Microsoft-centric enterprises** — Developer edition free for non-production use.



- **[Oracle Database](https://www.oracle.com/database/)**  

  **The enterprise RDBMS standard** for mission-critical workloads with advanced features (RAC, Data Guard, Exadata). **The most feature-complete commercial RDBMS** — licensing based on cores and named users.



- **[IBM Db2](https://www.ibm.com/products/db2)**  

  IBM's enterprise RDBMS with AI-powered optimization, pureXML, and strong mainframe integration. **The standard for IBM-centric enterprises** — Db2 Community Edition available on Docker.



- **[Amazon Aurora](https://aws.amazon.com/rds/aurora/)**  

  AWS's MySQL- and PostgreSQL-compatible cloud RDBMS with **5x throughput over standard MySQL** and **3x over PostgreSQL** . **The leading cloud-native RDBMS** — storage auto-scales to 128 TB.



- **[Google Cloud SQL](https://cloud.google.com/sql)**  

  Google's fully managed MySQL, PostgreSQL, and SQL Server. **The easiest migration path** for existing database workloads to GCP.



- **[SAP ASE](https://www.sap.com/products/sybase-ase.html)**  

  SAP's enterprise RDBMS (formerly Sybase ASE) with strong transaction processing and SAP integration.



## Open-Source GitHub Projects



- **[PostgreSQL](https://github.com/postgres/postgres)**  

  **The world's most advanced open-source relational database**, PostgreSQL License (permissive) with **17,000+ GitHub stars** . **ACID compliant with full transaction support, MVCC, and point-in-time recovery** . Features **JSONB, arrays, range types, full-text search, window functions, CTEs, and foreign data wrappers** . **Extensible architecture** — custom types, functions, operators, and extensions like **PostGIS (geospatial), TimescaleDB (time-series), and pgvector (AI embeddings)** . **The most feature-complete open-source RDBMS** — used by Apple, Instagram, and Reddit . **The de facto standard for modern applications** .



- **[MySQL](https://github.com/mysql/mysql-server)**  

  **The world's most popular open-source database**, GPL-2.0 licensed with **10,000+ GitHub stars** . **The default database for web applications** — powers WordPress, Facebook, and YouTube . **InnoDB storage engine** with ACID compliance and row-level locking . **Replication, partitioning, and sharding** for scale . **The most widely deployed RDBMS** — available on every cloud platform . **Best for web applications and read-heavy workloads** .



- **[MariaDB](https://github.com/MariaDB/server)**  

  **The community-developed fork of MySQL**, GPL-2.0 licensed with **5,000+ GitHub stars** . **Created by MySQL's original developers** after Oracle's acquisition . **Drop-in MySQL replacement** with additional storage engines (Aria, ColumnStore, MyRocks) . **More open development model** — features land faster than MySQL . **The preferred choice for MySQL users wanting community governance** . **Best for MySQL compatibility with more features** .



- **[SQLite](https://github.com/sqlite/sqlite)**  

  **The most deployed database in the world**, public domain with **6,000+ GitHub stars** . **Embedded, serverless, zero-configuration** — no separate process . **The standard for mobile apps, embedded systems, and local storage** — used by every iPhone, Android device, and web browser . **Single file database** — easy backup and transfer . **The best choice for embedded and local-first applications** .



- **[CockroachDB](https://github.com/cockroachdb/cockroach)**  

  **Distributed SQL database with PostgreSQL compatibility**, BSL licensed (free for most uses) with **30,000+ GitHub stars** . **Survives data center failures with no data loss** — built for global scale . **Horizontal scaling, geo-partitioning, and serializable isolation** . **The leading open-source distributed SQL database** — used by Netflix, Spotify, and Comcast . **Best for globally distributed applications requiring strong consistency** .



- **[YugabyteDB](https://github.com/yugabyte/yugabyte-db)**  

  **Distributed SQL database with PostgreSQL and Cassandra compatibility**, Apache-2.0 licensed with **9,000+ GitHub stars** . **Multi-region, multi-cloud deployment** with synchronous replication . **PostgreSQL-compatible** — reuse existing drivers and tools . **The most open distributed SQL database** — Apache 2.0 licensed . **Best for multi-cloud and geo-distributed workloads** .



- **[TiDB](https://github.com/pingcap/tidb)**  

  **Distributed SQL database with MySQL compatibility**, Apache-2.0 licensed with **37,000+ GitHub stars** . **HTAP (Hybrid Transactional/Analytical Processing)** — real-time analytics on transactional data . **Horizontal scaling, strong consistency, and MySQL protocol** . **The leading open-source HTAP database** — used by Square, Shopee, and Pinterest . **Best for real-time analytics alongside OLTP** .



- **[Firebird](https://github.com/FirebirdSQL/firebird)**  

  **Open-source RDBMS with excellent concurrency and small footprint**, IPL/IDPL licensed . **Embedded and server modes** — single file database . **Strong for ISV applications and embedded deployments** . **The best open-source alternative for embedded enterprise applications** .



- **[H2 Database](https://github.com/h2database/h2database)**  

  **Java SQL database with embedded and server modes**, MPL-2.0/Eclipse Public License . **The standard for Java testing and development** — used by Spring Boot default . **Best for Java applications needing lightweight database** .



- **[Apache Derby](https://github.com/apache/derby)**  

  **Java-based embedded RDBMS from Apache**, Apache-2.0 licensed . **Pure Java, zero administration** — ideal for Java applications . **Best for Java embedded database needs** .



- **[Firebird](https://github.com/FirebirdSQL/firebird)** — Already listed. **Excellent concurrency and small footprint** .



- **[HSQLDB](https://github.com/HSQLDB/HSQLDB)**  

  **Java SQL database with in-memory and disk modes**, BSD licensed . **The standard for Java unit testing** — used by many Java frameworks . **Best for testing and lightweight Java persistence** .



### NewSQL & Distributed SQL



- **[CockroachDB](https://github.com/cockroachdb/cockroach)** — Already listed. **The leading open-source distributed SQL** .

- **[YugabyteDB](https://github.com/yugabyte/yugabyte-db)** — Already listed. **Apache 2.0 distributed SQL** .

- **[TiDB](https://github.com/pingcap/tidb)** — Already listed. **HTAP with MySQL compatibility** .

- **[Vitess](https://github.com/vitessio/vitess)** — **MySQL sharding middleware from YouTube**, Apache-2.0 licensed with **18,000+ GitHub stars** . **Scales MySQL horizontally** — used by Slack, Square, and Etsy . **Best for scaling existing MySQL deployments** .

- **[Citus](https://github.com/citusdata/citus)** — **PostgreSQL extension for distributed tables**, AGPL-3.0 licensed . **Shards PostgreSQL across nodes** — part of Microsoft Azure PostgreSQL . **Best for scaling PostgreSQL without application changes** .

- **[Greenplum](https://github.com/greenplum-db/gpdb)** — **MPP data warehouse based on PostgreSQL**, Apache-2.0 licensed . **Best for analytical workloads on PostgreSQL** .



### Embedded & Specialized



- **[DuckDB](https://github.com/duckdb/duckdb)** — **In-process analytical database (OLAP)**, MIT licensed with **20,000+ GitHub stars** . **"SQLite for analytics"** — columnar storage with vectorized execution . **Best for analytical queries on embedded data** .

- **[libSQL](https://github.com/tursodatabase/libsql)** — **Open-source SQLite fork with replication and HTTP access**, MIT licensed . **The foundation for Turso** — SQLite at the edge . **Best for edge and serverless SQLite** .

- **[RQLite](https://github.com/rqlite/rqlite)** — **SQLite with Raft consensus for distributed deployment**, MIT licensed . **Replicated SQLite** — easy cluster setup . **Best for small distributed deployments** .



### Additional Strong Open-Source Options



- **Percona Server for MySQL** — Enhanced MySQL with performance and diagnostics .

- **Percona Server for PostgreSQL** — Enhanced PostgreSQL with additional features .

- **TimescaleDB** — Time-series extension for PostgreSQL, Apache-2.0/Timescale License .

- **PostGIS** — Geospatial extension for PostgreSQL, GPL-2.0 licensed .

- **pgvector** — Vector similarity search for PostgreSQL, PostgreSQL License .

- **Apache Cassandra** — Wide-column distributed database, Apache-2.0 licensed .

- **ScyllaDB** — Cassandra-compatible with higher performance, AGPL-3.0 licensed .

- **MongoDB** — Document database (not relational), SSPL licensed .

- **CouchDB** — Document database with HTTP API, Apache-2.0 licensed .



**Frameworks for building custom database solutions**: Choose based on workload and scale. **PostgreSQL** for the most feature-complete open-source RDBMS with extensibility . **MySQL** or **MariaDB** for web applications and read-heavy workloads . **SQLite** for embedded and local-first applications . **CockroachDB** or **YugabyteDB** for globally distributed SQL with strong consistency . **TiDB** for HTAP workloads . **DuckDB** for embedded analytics . **Vitess** or **Citus** for scaling existing MySQL/PostgreSQL deployments . Note that true enterprise RDBMS with vendor-supported SLAs, advanced security certifications, and proprietary features (Oracle RAC, SQL Server Always On) remains primarily commercial territory; open-source stacks provide strong ACID, replication, and scaling foundations that require integration for complete enterprise database operations.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Databases store sensitive business and personal data. Self-hosted solutions require proper security hardening, encryption at rest and in transit, access controls, and backup procedures.

- **License considerations**: CockroachDB uses BSL (free for most uses but not OSI open source), MongoDB uses SSPL (not OSI approved), and TimescaleDB has a mixed license. Verify licensing against your use case before committing .

- **PostgreSQL and MySQL have different strengths** — PostgreSQL for advanced features and extensibility; MySQL/MariaDB for simplicity and web-scale read performance . Evaluate against your workload.

- **Distributed SQL adds operational complexity** — CockroachDB, YugabyteDB, and TiDB require expertise in consensus, replication, and geo-distribution. Evaluate operational capacity before deployment .

- The open-source ecosystem provides strong ACID, replication, and scaling foundations, but **vendor-supported SLAs, advanced security certifications, and proprietary enterprise features** remain primarily commercial offerings.



---



**Made for database administrators, backend developers, and infrastructure architects.**  

Let's make relational database management more open, transparent, and accessible.
