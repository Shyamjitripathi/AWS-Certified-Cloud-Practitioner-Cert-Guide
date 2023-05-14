## Database Services

- Amazon Aurora :is a MySQL and PostgreSQL compatible relational database engine that combines the
speed and availability of high-end commercial databases with the simplicity and cost-eﬀectiveness of
open source databases. Amazon Aurora is up to ﬁve times faster than standard MySQL databases and three times faster than
standard PostgreSQL databases. It provides the security, availability, and reliability of commercialdatabases at 1/10th the cost. Amazon Aurora is fully managed by Amazon Relational Database Service
(Amazon RDS), which automates time-consuming administration tasks such as hardware provisioning,
database setup, patching, and backups.Amazon Aurora features a distributed, fault-tolerant, self-healing storage system that auto-scales up
to 128TB per database instance. It delivers high performance and availability with up to 15 low-latency
read replicas, point-in-time recovery, continuous backup to Amazon S3, and replication across three
Availability Zones (AZs).

- Amazon DynamoDB :  is a key-value and document database that delivers single-digit millisecond
performance at any scale. It's a fully managed, multiregion, multimaster database with built-in security,
backup and restore, and in-memory caching for internet-scale applications. DynamoDB can handle more
than 10 trillion requests per day and support peaks of more than 20 million requests per second.
Many of the world's fastest growing businesses such as Lyft, Airbnb, and Redﬁn, as well as enterprises
such as Samsung, Toyota, and Capital One, depend on the scale and performance of DynamoDB to
support their mission-critical workloads.Hundreds of thousands of AWS customers have chosen DynamoDB as their key-value and document
database for mobile, web, gaming, ad tech, Internet of Things (IoT), and other applications that need
low-latency data access at any scale. Create a new table for your application and let DynamoDB handle
the rest.

- Amazon ElastiCache : is a web service that makes it easy to deploy, operate, and scale an in-memory
cache in the cloud. The service improves the performance of web applications by allowing you to retrieve
information from fast, managed, in-memory caches, instead of relying entirely on slower disk-based
databases.Amazon ElastiCache supports two open-source in-memory caching engines:
• Redis - a fast, open-source, in-memory key-value data store for use as a database, cache, message
broker, and queue. 
• Memcached - a widely adopted memory object caching system. Amazon ElastiCache for Memcached
is protocol compliant with Memcached, so popular tools that you use today with existing Memcached
environments will work seamlessly with the service.

- Amazon Neptune : is a fast, reliable, fully-managed graph database service that makes it easy to build and
run applications that work with highly connected datasets. The core of Amazon Neptune is a purpose-
built, high-performance graph database engine optimized for storing billions of relationships and
querying the graph with milliseconds latency. Amazon Neptune supports popular graph models Property
Graph and W3C's RDF, and their respective query languages Apache TinkerPop Gremlin and SPARQL,
allowing you to easily build queries that eﬃciently navigate highly connected datasets. Neptune powers
graph use cases such as recommendation engines, fraud detection, knowledge graphs, drug discovery,
and network security.Amazon Neptune is highly available, with read replicas, point-in-time recovery, continuous backup to
Amazon S3, and replication across Availability Zones. Neptune is secure with support for encryption at
rest. Neptune is fully-managed, so you no longer need to worry about database management tasks such
as hardware provisioning, software patching, setup, conﬁguration, or backups.

- Amazon Relational Database Service(Amazon RDS) : makes it easy to set up, operate, and scale a
relational database in the cloud. It provides cost-eﬃcient and resizable capacity while automating time-
consuming administration tasks such as hardware provisioning, database setup, patching and backups.
It frees you to focus on your applications so you can give them the fast performance, high availability,
security and compatibility they need.Amazon RDS is available on several database instance types - optimized for memory, performance or
I/O - and provides you with six familiar database engines to choose from, including Amazon Aurora,
PostgreSQL, MySQL, MariaDB, Oracle Database, and SQL Server. You can use the AWS Database
Migration Service to easily migrate or replicate your existing databases to Amazon RDS.

- Amazon Quantum Ledger Database (Amazon QLDB) : is a fully managed ledger database that provides a transparent, immutable, and
cryptographically veriﬁable transaction log owned by a central trusted authority. Amazon QLDB tracks
each and every application data change and maintains a complete and veriﬁable history of changes over
time.

- Amazon Timestream : is a fast, scalable, fully managed time series database service for IoT and
operational applications that makes it easy to store and analyze trillions of events per day at 1/10th the
cost of relational databases. Driven by the rise of IoT devices, IT systems, and smart industrial machines,
time-series data — data that measures how things change over time — is one of the fastest growing
data types. Time-series data has speciﬁc characteristics such as typically arriving in time order form, data
is append-only, and queries are always over a time interval. While relational databases can store this
data, they are ineﬃcient at processing this data as they lack optimizations such as storing and retrieving
data by time intervals.

- Amazon DocumentDB (with MongoDB compatibility) : is a fast, scalable, highly available, and fully
managed document database service that supports MongoDB workloads.
Amazon DocumentDB (with MongoDB compatibility) is designed from the ground-up to give you the
performance, scalability, and availability you need when operating mission-critical MongoDB workloads
at scale. Amazon DocumentDB (with MongoDB compatibility) implements the Apache 2.0 open source
MongoDB 3.6 and 4.0 APIs by emulating the responses that a MongoDB client expects from a MongoDB
server, allowing you to use your existing MongoDB drivers and tools with Amazon DocumentDB (with
MongoDB compatibility).
