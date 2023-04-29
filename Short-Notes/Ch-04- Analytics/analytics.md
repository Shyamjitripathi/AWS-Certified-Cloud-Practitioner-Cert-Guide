## Analytics-Services

- Amazon Athena : is a serverless, interactive query service that allows users to easily analyze data in Amazon S3 using standard SQL. It is designed to be user-friendly, with no need for complex ETL jobs to prepare data for analysis. Athena is integrated with AWS Glue Data Catalog, which allows users to create a unified metadata repository, discover schemas, and maintain schema versioning. Users only pay for the queries they run, and most results are delivered within seconds.
- Amazon CloudSearch : Amazon CloudSearch is a managed service in the AWS Cloud that makes it simple and cost-eﬀective
to set up, manage, and scale a search solution for your website or application. Amazon CloudSearch
supports 34 languages and popular search features such as highlighting, autocomplete, and geospatial
search.
- Amazon EMR : is the industry-leading cloud big data platform for processing vast amounts of data
using open source tools such as Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi,
and Presto. Amazon EMR makes it easy to set up, operate, and scale your big data environments by
automating time-consuming tasks such as provisioning capacity and tuning clusters. With Amazon EMR,
you can run petabyte-scale analysis at less than half of the cost of traditional on-premises solutions and
over 3x faster than standard Apache Spark. You can run workloads on Amazon EC2 instances, on Amazon
Elastic Kubernetes Service (Amazon EKS) clusters, or on-premises using Amazon EMR on AWS Outposts.
- Amazon FinSpace :  is a data management and analytics service specifically designed for the financial services industry. It helps financial organizations to quickly find and prepare petabytes of data for analysis, reducing the time it takes from months to minutes. With FinSpace, users can collect and catalog data by relevant business concepts, making it easy to discover and share data across the organization. The service includes a library of over 100 functions for data preparation and allows users to define data access policies in one place while maintaining compliance and activity reporting.
- Amazon Kinesis : makes it easy to collect, process, and analyze real-time, streaming data so you can get
timely insights and react quickly to new information. Amazon Kinesis oﬀers key capabilities to cost-
eﬀectively process streaming data at any scale, along with the ﬂexibility to choose the tools that best
suit the requirements of your application. With Amazon Kinesis, you can ingest real-time data such as
video, audio, application logs, website clickstreams, and IoT telemetry data for machine learning (ML),
analytics, and other applications. Amazon Kinesis enables you to process and analyze data as it arrives
and respond instantly instead of having to wait until all your data is collected before the processing can
begin.
- Amazon Kinesis Data Firehose :  is a fully managed service that allows users to capture, transform, and load streaming data into data stores and analytics tools like Amazon S3, Amazon Redshift, and Splunk, enabling near real-time analytics with existing business intelligence tools. It can automatically scale to match the throughput of your data and requires no ongoing administration. The service can batch, compress, transform, and encrypt the data before loading it, reducing storage usage and increasing security. Users can easily create a delivery stream from the AWS Management Console, configure it with a few clicks, and start sending data from hundreds of thousands of data sources in just a few minutes. It also allows users to convert incoming data to columnar formats like Apache Parquet and Apache ORC, for cost-effective storage and analytics.


<hr>
Amazon Kinesis Data Analytics
Amazon Kinesis Data Analytics is the easiest way to analyze streaming data, gain actionable insights,
and respond to your business and customer needs in real time. Amazon Kinesis Data Analytics reduces
the complexity of building, managing, and integrating streaming applications with other AWS services.
SQL users can easily query streaming data or build entire streaming applications using templates and an
interactive SQL editor. Java developers can quickly build sophisticated streaming applications using open
source Java libraries and AWS integrations to transform and analyze data in real-time.
Amazon Kinesis Data Analytics takes care of everything required to run your queries continuously and
scales automatically to match the volume and throughput rate of your incoming data.
Amazon Kinesis Data Streams
Amazon Kinesis Data Streams is a massively scalable and durable real-time data streaming service.
Kinesis Data Streams can continuously capture gigabytes of data per second from hundreds of thousands
of sources such as website clickstreams, database event streams, ﬁnancial transactions, social media
feeds, IT logs, and location-tracking events. The data collected is available in milliseconds to enable real-
time analytics use cases such as real-time dashboards, real-time anomaly detection, dynamic pricing, and
more.
Amazon Kinesis Video Streams
Amazon Kinesis Video Streams makes it easy to securely stream video from connected devices to AWS
for analytics, ML, playback, and other processing. Kinesis Video Streams automatically provisions and
elastically scales all the infrastructure needed to ingest streaming video data from millions of devices. It
also durably stores, encrypts, and indexes video data in your streams, and allows you to access your data
through easy-to-use APIs. Kinesis Video Streams enables you to playback video for live and on-demand
viewing, and quickly build applications that take advantage of computer vision and video analytics
through integration with Amazon Rekognition Video, and libraries for ML frameworks such as Apache
MxNet, TensorFlow, and OpenCV.
Amazon OpenSearch Service
Amazon OpenSearch Service (OpenSearch Service) makes it easy to deploy, secure, operate, and scale
OpenSearch to search, analyze, and visualize data in real-time. With Amazon OpenSearch Service,
you get easy-to-use APIs and real-time analytics capabilities to power use-cases such as log analytics,
13Overview of Amazon Web Services AWS Whitepaper
Amazon Redshift
full-text search, application monitoring, and clickstream analytics, with enterprise-grade availability,
scalability, and security. The service oﬀers integrations with open-source tools such as OpenSearch
Dashboards and Logstash for data ingestion and visualization. It also integrates seamlessly with other
AWS services such as Amazon Virtual Private Cloud (Amazon VPC), AWS Key Management Service (AWS
KMS), Amazon Kinesis Data Firehose, AWS Lambda, AWS Identity and Access Management (IAM), Amazon
Cognito, and Amazon CloudWatch, so that you can go from raw data to actionable insights quickly.
Amazon Redshift
Amazon Redshift is the most widely used cloud data warehouse. It makes it fast, simple and cost-
eﬀective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools.
It allows you to run complex analytic queries against terabytes to petabytes of structured and semi-
structured data, using sophisticated query optimization, columnar storage on high-performance storage,
and massively parallel query completion. Most results come back in seconds. You can start small for just
$0.25 per hour with no commitments and scale out to petabytes of data for $1,000 per terabyte per
year, less than a tenth the cost of traditional on-premises solutions.
Amazon Redshift Serverless
Amazon Redshift Serverless makes it easier to run and scale analytics without having to manage your
data warehouse infrastructure. Developers, data scientists, and analysts can work across databases, data
warehouses, and data lakes to build reporting and dashboarding applications, perform near real-time
analytics, share and collaborate on data, and build and train machine learning (ML) models. Go from
large amounts of data to insights in seconds. Amazon Redshift Serverless automatically provisions and
intelligently scales data warehouse capacity to deliver fast performance for even the most demanding
and unpredictable workloads, and you pay only for what you use. Just load data and start querying right
away in Amazon Redshift Query Editor or in your favorite business intelligence (BI) tool and continue
to enjoy the best price performance and familiar SQL features in an easy-to-use, zero administration
environment.
Amazon QuickSight
Amazon QuickSight is a fast, cloud-powered business intelligence (BI) service that makes it easy for you
to deliver insights to everyone in your organization. QuickSight lets you create and publish interactive
dashboards that can be accessed from browsers or mobile devices. You can embed dashboards into your
applications, providing your customers with powerful self-service analytics. Amazon QuickSight easily
scales to tens of thousands of users without any software to install, servers to deploy, or infrastructure to
manage.
AWS Data Exchange
AWS Data Exchange makes it easy to ﬁnd, subscribe to, and use third-party data in the cloud. Qualiﬁed
data providers include category-leading brands such as Reuters, who curate data from over 2.2 million
unique news stories per year in multiple languages; Change Healthcare, who process and anonymize
more than 14 billion healthcare transactions and $1 trillion in claims annually; Dun & Bradstreet, who
maintain a database of more than 330 million global business records; and Foursquare, whose location
data is derived from 220 million unique consumers and includes more than 60 million global commercial
venues.
Once subscribed to a data product, you can use the AWS Data Exchange API to load data directly into
Amazon S3 and then analyze it with a wide variety of AWS analytics and ML services. For example,
property insurers can subscribe to data to analyze historical weather patterns to calibrate insurance
coverage requirements in diﬀerent geographies; restaurants can subscribe to population and location
data to identify optimal regions for expansion; academic researchers can conduct studies on climate
change by subscribing to data on carbon dioxide emissions; and healthcare professionals can subscribe to
aggregated data from historical clinical trials to accelerate their research activities.
For data providers, AWS Data Exchange makes it easy to reach the millions of AWS customers migrating
to the cloud by removing the need to build and maintain infrastructure for data storage, delivery, billing,
and entitling.
AWS Data Pipeline
AWS Data Pipeline is a web service that helps you reliably process and move data between diﬀerent
AWS compute and storage services, as well as on-premises data sources, at speciﬁed intervals. With AWS
Data Pipeline, you can regularly access your data where it’s stored, transform and process it at scale, and
eﬃciently transfer the results to AWS services such as Amazon S3 (p. 85), Amazon RDS (p. 33),
Amazon DynamoDB (p. 32), and Amazon EMR (p. 12).
AWS Data Pipeline helps you easily create complex data processing workloads that are fault tolerant,
repeatable, and highly available. You don’t have to worry about ensuring resource availability, managing
inter-task dependencies, retrying transient failures or timeouts in individual tasks, or creating a failure
notiﬁcation system. AWS Data Pipeline also allows you to move and process data that was previously
locked up in on-premises data silos.
AWS Glue
AWS Glue is a fully managed extract, transform, and load (ETL) service that makes it easy for customers
to prepare and load their data for analytics. You can create and run an ETL job with a few clicks in the
AWS Management Console. You simply point AWS Glue to your data stored on AWS, and AWS Glue
discovers your data and stores the associated metadata (such as table deﬁnition and schema) in the AWS
Glue Data Catalog. Once cataloged, your data is immediately searchable, queryable, and available for
ETL.
AWS Lake Formation
AWS Lake Formation is a service that makes it easy to set up a secure data lake in days. A data lake is
a centralized, curated, and secured repository that stores all your data, both in its original form and
prepared for analysis. A data lake enables you to break down data silos and combine diﬀerent types of
analytics to gain insights and guide better business decisions.
However, setting up and managing data lakes today involves a lot of manual, complicated, and time-
consuming tasks. This work includes loading data from diverse sources, monitoring those data ﬂows,
setting up partitions, turning on encryption and managing keys, deﬁning transformation jobs and
monitoring their operation, re-organizing data into a columnar format, conﬁguring access control
settings, deduplicating redundant data, matching linked records, granting access to data sets, and
auditing access over time.
Creating a data lake with Lake Formation is as simple as deﬁning where your data resides and what
data access and security policies you want to apply. Lake Formation then collects and catalogs data
from databases and object storage, moves the data into your new Amazon S3 data lake, cleans and
classiﬁes data using ML algorithms, and secures access to your sensitive data. Your users can then access
a centralized catalog of data which describes available data sets and their appropriate usage. Your users
then leverage these data sets with their choice of analytics and ML services, such as Amazon EMR for
Apache Spark, Amazon Redshift, Amazon Athena, SageMaker, and Amazon QuickSight.
Amazon Managed Streaming for Apache Kafka
(Amazon MSK)
Amazon Managed Streaming for Apache Kafka (Amazon MSK) is a fully managed service that makes
it easy for you to build and run applications that use Apache Kafka to process streaming data. Apache
Kafka is an open-source platform for building real-time streaming data pipelines and applications.
With Amazon MSK, you can use Apache Kafka APIs to populate data lakes, stream changes to and from
databases, and power ML and analytics applications.
Apache Kafka clusters are challenging to setup, scale, and manage in production. When you run Apache
Kafka on your own, you need to provision servers, conﬁgure Apache Kafka manually, replace servers
when they fail, orchestrate server patches and upgrades, architect the cluster for high availability, ensure
data is durably stored and secured, setup monitoring and alarms, and carefully plan scaling events to
support load changes. Amazon MSK makes it easy for you to build and run production applications on
Apache Kafka without needing Apache Kafka infrastructure management expertise. That means you
spend less time managing infrastructure and more time building applications.
With a few clicks in the Amazon MSK console you can create highly available Apache Kafka clusters
with settings and conﬁguration based on Apache Kafka’s deployment best practices. Amazon MSK
automatically provisions and runs your Apache Kafka clusters. Amazon MSK continuously monitors
cluster health and automatically replaces unhealthy nodes with no downtime to your application. In
addition, Amazon MSK secures your Apache Kafka cluster by encrypting data at rest.
