# Awesome Entity Framework 6

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Entity Framework is an open-source ORM framework for .NET applications. It is the official data access platform for Microsoft.

A curated list of awesome entity framework 6 libraries, packages, and documentation.

### Contributing

Suggestions and contributions are always welcome! Make sure to read the <a href="https://github.com/zzzprojects/awesome-entity-framework-6/blob/master/CONTRIBUTING.md">contribution guidelines</a> for more information before submitting a pull request.

### Contents

- [Awesome Entity Framework 6](#awesome-entity-framework-6)
  - [Documentation and Learning](#documentation-and-learning)
  - [Supported Packages](#supported-packages)
  - [Unsupported Packages](#supported-packages)
  - [Providers](#providers)

## Documentation and Learning

 - [Entity Framework Docs](https://github.com/aspnet/EntityFramework.Docs) - Official documentation for Entity Framework by Microsoft.
 - [Entity Framework Tutorial](http://entityframework.net/)
 - [Entityframeworktutorial.net](http://www.entityframeworktutorial.net/) - Learn Entity Framework using simple yet practical examples on EntityFrameworkTutorial.net for free
 - [RIP Tutorial](https://riptutorial.com/entity-framework) - Archived Stack Overflow Documentation (Multi-Language)
 - [Knowledge base](https://entityframework.net/knowledge-base) - Translated posts from Stack Overflow
 - [Google](http://www.letmegooglethat.com/?q=Entity+Framework) - Up-and-coming search engine ;)
 - Books
    - [Programming Entity Framework, 2nd Edition](http://shop.oreilly.com/product/9780596807252.do) - Julia Lerman must have book
    - [Programming Entity Framework: Code First](http://shop.oreilly.com/product/0636920022220.do) - Focus on the code first part of EF
 - Videos
    - [Pluralsight](https://www.pluralsight.com/courses/entity-framework-6-getting-started) - Online class to get started with EF 6
    - [Microsoft Virtual Academy](https://mva.microsoft.com/en-us/training-courses/implementing-entity-framework-with-mvc-8931?l=e2H2lDC3_8304984382) - Online class from MVA on how to use EF with MVC
 
## Supported Packages

 - [EntityFramework-Classic](https://github.com/zzzprojects/EntityFramework-Classic) - Entity Framework Classic is a supported version from the latest EF6 code base. It supports .NET Framework and .NET Core and overcomes some EF limitations by adding tons of must-haves built-in features.
 - [EntityFramework-Extensions](https://github.com/zzzprojects/EntityFramework-Extensions) - Improve Entity Framework performance with Bulk SaveChanges and Bulk Operations.
 - [EntityFramework-Plus](https://github.com/zzzprojects/EntityFramework-Plus) - Improve Entity Framework performance and overcome limitations with MUST-HAVE features.
 - [EntityFramework-Effort](https://github.com/zzzprojects/EntityFramework-Effort) - An Effort is a powerful tool that enables a convenient way to create automated tests for Entity Framework based applications.
 - [EntityFramework.DynamicFilters](https://github.com/zzzprojects/EntityFramework.DynamicFilters) - Create global and scoped filters for Entity Framework queries. The filters are automatically applied to every query and can be used to support use cases such as Multi-Tenancy, Soft Deletes, Active/Inactive, etc.
 - [GraphDiff](https://github.com/zzzprojects/GraphDiff) - DbContext extension methods for Entity Framework Code First, that allows you to save an entire detached Model/Entity, with child Entities and Lists, to the database without writing the code to do it.
 - [Audit.EntityFramework](https://github.com/thepirat000/Audit.NET/tree/master/src/Audit.EntityFramework) - Audit.EntityFramework provides the infrastructure to log interactions with the EF DbContext.
 - [EntityFramework.Testing](https://github.com/scott-xu/EntityFramework.Testing) - EntityFramework.Testing provides an implementation of DbAsyncQueryProvider that can be used when testing a component that uses async queries with EntityFramework.
 - [EntityFramework.Utilities](https://github.com/RudeySH/EntityFramework.Utilities) - Provides extensions for EntityFramework that doesn't exist out of the box like delete and update by query and bulk inserts.
 - [EntityFramework-Reverse-POCO-Code-First-Generator](https://github.com/sjh37/EntityFramework-Reverse-POCO-Code-First-Generator) - EntityFramework Reverse POCO Code First Generator - Beautifully generated code-first code that is fully customizable. 
 - [EFCache](https://github.com/moozzyk/EFCache) - EntityFramework.Cache provides a second level cache for Entity Framework 6.1 and newer.
 - [LINQKit](https://github.com/scottksmith95/LINQKit) - LINQKit is a free set of extensions for LINQ to SQL and Entity Framework power users.
 - [AutoMapper.EF6](https://github.com/AutoMapper/AutoMapper.EF6) - Extensions for AutoMapper and EF6.
 - [EntityFramework.Triggers](https://github.com/NickStrupat/EntityFramework.Triggers) - Adds events for entity inserting, inserted, updating, updated, deleting, and deleted.
 - [EntityFrameworkExtras](https://github.com/Fodsuk/EntityFrameworkExtras) - EntityFrameworkExtras provides some useful additions to EntityFramework such as executing Stored Procedures with User-Defined Table Types and Output Parameters.
 - [EntityFramework.Functions](https://github.com/Dixin/EntityFramework.Functions) - EntityFramework.Functions library implements Entity Framework code first support for stored procedures, TVFs and SVFs, etc.
 - [EntityFramework.BulkInsert](https://github.com/ghost1face/EntityFramework.BulkInsert) - The purpose of this library is for performing Bulk Inserts using EntityFramework 6 and your existing DbContext instance to perform faster inserts instead of generating multiple insert statements for a collection of strongly typed objects.
 - [EntityFramework.Toolkit](https://github.com/thomasgalliker/EntityFramework.Toolkit) - EntityFramework.Toolkit is a library which provides implementations for EntityFramework best practices, patterns, utilities, and extensions.
 - [EFDesigner](https://github.com/msawczyn/EFDesigner) - Entity Framework visual design surface and code-first code generation for EF6, Core and beyond.
 - [CodeFirstFunctions](https://github.com/moozzyk/CodeFirstFunctions) - Store Functions for EntityFramework CodeFirst.
 - [EntityFramework Profiler](https://www.hibernatingrhinos.com/products/EFProf) - Entity Framework Profiler is a real-time visual debugger allowing a development team to gain valuable insight and perspective into their usage of Entity Framework.
 - [MassTransit.EntityFramework](https://github.com/MassTransit/MassTransit) - MassTransit Entity Framework support; MassTransit is a message-based distributed application framework for .NET [http://masstransit-project.com/](http://masstransit-project.com/)
 - [SQLiteCodeFirst](https://github.com/msallin/SQLiteCodeFirst) - Creates an SQLite Database based on an EdmModel by using Entity Framework CodeFirst.
 - [IdentityServer4.EntityFramework](https://github.com/IdentityServer/IdentityServer4.EntityFramework) - EntityFramework persistence layer for IdentityServer4
 - [PommaLabs.KVLite.EntityFramework](https://gitlab.com/pommalabs/kvlite) - KVLite is a partition-based key-value cache built for SQL RDBMSs. This package contains an Entity Framework query cache provider.
 - [Stove.EntityFramework](https://github.com/stoveproject/Stove) - Domain Driven Design oriented application framework, meets CRUD needs.
 - [EntityFrameworkMock](https://github.com/huysentruitw/entity-framework-mock) - Easy Mock wrapper for mocking EF6 DbContext and DbSet using Moq or NSubstitute.
 - [EntityFramework.PrimaryKey](https://github.com/NickStrupat/EntityFramework.PrimaryKey) - Retrieve the primary key (including composite keys) from any entity.
 - [DelegateDecompiler.EntityFramework](https://github.com/hazzik/DelegateDecompiler) - A library which is able to decompile a delegate or a method body to its lambda representation.

## Unsupported Packages

 - [EntityFramework.Extended](https://github.com/zzzprojects/EntityFramework.Extended) - Add-on feature for Entity Framework.
 - [EntityFramework.Filters](https://github.com/jbogard/EntityFramework.Filters) - Filters implementation for Entity Framework.
 - [EntityFramework.CommonTools](https://github.com/gnaeus/EntityFramework.CommonTools) - Extensions, Auditing, Concurrency Checks, JSON properties and Transaction Logs for EntityFramework and EFCore.
 - [AspNet.Identity.EntityFramework.Multitenant](https://github.com/JSkimming/AspNet.Identity.EntityFramework.Multitenant) - Multi-tenant support for ASP.NET Identity using Entity Framework.
 - [AuditDbContext](http://auditdbcontext.codeplex.com/) - AuditDbContext provides entity change auditing for Entity Framework POCO entities.
 - [EFAuditing](https://github.com/johannbrink/EFAuditing) - EFAuditing is a library that implements Auditing for Entity Framework Core based DbContexts. It is extensible to allow other logging providers like MongoDB, Azure tables, etc.
 - [EntityFramework.Utilities](https://github.com/MikaelEliasson/EntityFramework.Utilities) - Provides extensions for EntityFramework that doesn't exist out of the box like delete and update by query and bulk inserts.
 - [TrackerEnabledDbContext](https://github.com/bilal-fazlani/tracker-enabled-dbcontext) - Tracker-enabled DbContext offers you to implement full auditing in your database.
 - [Speedy.EntityFramework](https://github.com/BobbyCannon/Speedy) - Speedy is a simple easy to use Entity Framework unit testing framework.
 - [EFBulkInsert](https://github.com/andreisabau/EFBulkInsert) - Provides an extension method over the Entity Framework DbContext for bulk insertion of entities.

## Providers

 - [EntityFramework.SqlServerCompact](https://www.nuget.org/packages/EntityFramework.SqlServerCompact) - Allows SQL Server Compact 4.0 to be used with Entity Framework.
 - [System.Data.SQLite](https://www.nuget.org/packages/System.Data.SQLite/) - The official SQLite database engine for both x86 and x64 along with the ADO.NET provider.  This package includes support for LINQ and Entity Framework 6.
 - [Connector/NET](https://dev.mysql.com/downloads/connector/net/) - Connector/Net is a fully-managed ADO.NET driver for MySQL.
 - [Oracle.ManagedDataAccess.EntityFramework](https://www.nuget.org/packages/Oracle.ManagedDataAccess.EntityFramework/) - Official Oracle ODP.NET, Managed Entity Framework Driver.
 - [EntityFramework6.Npgsql](https://github.com/npgsql/EntityFramework6.Npgsql) - Entity Framework 6 provider for PostgreSQL
 - [Npgsql.EF6](https://www.nuget.org/packages/Npgsql.EF6/) - Npgsql is a .NET data provider for PostgreSQL. It is implemented in C#. Works with Postgresql 7.x and above.
 - [Firebird Entity Framework Provider](http://www.firebirdsql.org/en/net-provider/) - The .NET Data provider is written in C# and provides a high-performance, native implementation of the Firebird API.
 - [Devart](https://www.devart.com/dotconnect/) - Devart dotConnect is a commercial third-party provider. Entity Framework support is only available in paid versions of dotConnect.
 - [CData Software providers](https://www.cdata.com/ado/) - A third-party providers from CData Software for a variety of data stores including Salesforce, Azure Table Storage, MySql, and many more.
 - [VFPEntityFrameworkProvider2](https://www.nuget.org/packages/VFPEntityFrameworkProvider2/) - Entity Framework 6 Provider for VFP data.
