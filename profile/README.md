# Cinch
Cinch is a database migration system, designed to be extendable and configurable while maintaining simplicity.
Cinch's primary goal is to make database/schema version management easy but powerful:

* PostgreSQL, MySQL, MariaDB, SQL Server, Azure SQL Database, SQLite
* Tested in Google Cloud Platform, AWS RDS, Azure
* Support for SQL and PHP migrations
* Easy to configure or integrate into PHP applications
* 100% framework-agnostic
* Store history in a database other than the target: filesystem, GitHub, GitLab, Azure DevOps Services
* Ability to source migrations directly from version control
* Lifecycle hooks during a deployment: `migrate` or `rollback`
* CI/CD pipeline friendly
* Team-oriented management

Please see the [Cinch Documentation](https://www.cinch.live) for more information.