# Database centric cloud solution hands-on on Alibaba Cloud

| Solution | Description | Related Cloud Services | Video Tutorial | Solution Page on Alibaba Cloud |
| :------: | :---------: | :--------------------: | :------------: | :----------------------------: |
| [Cloud Native WordPress on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-cloud-native-web-hosting) | Quick start with Wordpress on Alibaba Cloud with cloud native features such as high availability, auto-scaling, etc. | EIP, SLB, ECS, ESS, Redis, PolarDB MySQL | [:clapper: Part 1](https://www.youtube.com/watch?v=TnWaGHBxPuw)  [:clapper: Part 2](https://www.youtube.com/watch?v=POQ_nxjnIYM) | [:beginner:](https://www.alibabacloud.com/architecture/solution-implementation/building-auto-scaling-wordpress-website-on-alibaba-cloud) |
| [WordPress (Marketplace) on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-marketplace-wordpress) | Quick start with Wordpress (Marketplace image) on Alibaba Cloud with different levels of service combination with price estimation. | EIP, SLB, ECS, ESS, Redis, RDS MySQL, PolarDB MySQL |  | [:beginner:](https://www.alibabacloud.com/architecture/solution-wordpress-ecs-marketplace-image) |
| [Scoreboard of Rose Bowl Games powdered by Redis & MySQL - Use Terraform To Provision All Resources](https://github.com/alibabacloud-howto/solution-mysql-redis-cache-simple) | The simplest solution for RDS MySQL database caching with Redis. This solution relies on the expiration time (TTL) of the key in Redis. Redis will not be updated proactively when MySQL is updated. This approach is simple to implement, but the inconsistency duration may be very long especially for the scenario that the read request is very frequent and the expiration time is relatively long, a lot of long-term dirty data will be generated. | ECS, Redis, RDS MySQL | [:clapper:](https://www.youtube.com/watch?v=POQ_nxjnIYM) | [:beginner:](https://www.alibabacloud.com/architecture/solution-mysql-redis-cache-simple) |
| [Redis Data Synchronization with RDS MySQL Using Canal & Kafka](https://github.com/alibabacloud-howto/solution-mysql-redis-canal-kafka-sync) | This solution uses Kafka and Canal to achieve data synchronization between RDS MySQL and Redis. | ECS, RDS MySQL, Redis, Kafka, Canal | [:clapper:](https://www.youtube.com/watch?v=O-GoA6182mI) | [:beginner:](https://www.alibabacloud.com/architecture/solution-mysql-redis-canal-kafka-sync) |
| [Deploy MongoDB Instances in Multiple Regions Automatically Using Terraform](https://github.com/alibabacloud-howto/solution-mongodb-multiregion-sync) | Using MongoShake deployed on ECS to one-way synchronize 2 MongoDB deployed in 2 regions respectively. | ECS, MongoDB, MongoShake | [:clapper:](https://www.youtube.com/watch?v=k6zUZcw6CU4) | [:beginner:](https://www.alibabacloud.com/architecture/solution-implementation/deploy-mongodb-instances-in-multiple-regions) |
| [Create Online Game Leaderboard on Redis](https://github.com/alibabacloud-howto/solution-online-leaderboard-redis) | Leaderboard sample for Gaming on cloud. This sample contains the Terraform scripts to provision an ECS and a Redis instance on Alibaba Cloud region, also there is a sample for setting up Java development environment on ECS and running a Leaderboard. | ECS, Redis | [:clapper:](https://www.youtube.com/watch?v=LMsMqYz9ik8) | [:beginner:](https://www.alibabacloud.com/architecture/solution-gaming-leaderboard-redis) |
| [Cloud Native Web App on Alibaba Cloud: COVID-19 Tracker](https://github.com/alibabacloud-howto/solution-covid19-tracker) | Deploy simple cloud native web app on Alibaba Cloud to visualize the spread and impact of Covid-19, subscribe for daily updates, and view stats. | EIP, ECS, RDS MySQL | | [:beginner:](https://www.alibabacloud.com/architecture/solution-deploy-covid19-tracker-app) |
| [Deploy and Run Netflix Dispatch on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/netflix_dispatch) | Running open source project Netflix Dispatch on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). | EIP, ECS, RDS PostgreSQL | | [:beginner:](https://www.alibabacloud.com/architecture/solution-deploy-netflix-dispatch) |
| [Deploy and Run Apache Superset on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/apache-superset) | Running open source project Apache Superset on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). | EIP, ECS, RDS PostgreSQL | [:clapper:](https://www.youtube.com/watch?v=C0uFuVD0vHw) | [:beginner:](https://www.alibabacloud.com/architecture/deploy-superset) |
| [Deploy and Run Redash on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/redash) | Running open source project Redash on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). | EIP, ECS, RDS PostgreSQL | [:clapper:](https://www.youtube.com/watch?v=BXRIhoZNlGA) | [:beginner:](https://www.alibabacloud.com/architecture/deploy-redash) |
| [Deploy and Run Apache OFBiz on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/apache-ofbiz) | Running open source project Apache OFBiz on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). | EIP, ECS, RDS MySQL | | [:beginner:](https://www.alibabacloud.com/architecture/solution-deploy-apache-ofbiz) |
| [Deploy and Run Apache Airflow on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/apache-airflow) | Running open source project Apache Airflow on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). We also show a simple data migration task deployed and run in Airflow to migrate data between 2 databases. | EIP, ECS, RDS PostgreSQL | [:clapper:](https://www.youtube.com/watch?v=3JRFngjEcUg) | [:beginner:](https://www.alibabacloud.com/architecture/solution-deploy-apache-airflow) |
| [Deploy and Run Azkaban on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/azkaban) | Running open source project Azkaban on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). We also show a simple data preparation and migration task deployed and run in Azkaban to prepare and migrate data between 2 databases. | EIP, ECS, RDS MySQL, RDS PostgreSQL | [:clapper:](https://www.youtube.com/watch?v=wKMdR_loU4I) | [:beginner:](https://www.alibabacloud.com/architecture/solution-deploy-azkaban) |
| [Build and Run ETL Data Pipeline and BI with Luigi and Metabase on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/luigi_metabase) | Running open source project Luigi and Metabase on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). We also show a simple ETL data pipeline deployed and run in Luigi and BI report run in Metabase with RDS PostgreSQL. | EIP, ECS, RDS PostgreSQL | [:clapper:](https://www.youtube.com/watch?v=fV_fbkijAKQ) | |
| [Running TPC-H benchmark on AnalyticDB PostgreSQL](https://github.com/alibabacloud-howto/solution-adbpg-labs/tree/master/benchmark-tpc-h) | The full steps of generating TPC-H data set and running TPC-H 22 queries on AnalyticDB PostgreSQL. | EIP, ECS, OSS, AnalyticDB PostgreSQL | [:clapper:](https://www.youtube.com/watch?v=yR3jVBQkrzU) | [:beginner:](https://www.alibabacloud.com/architecture/solution-deploy-tpc-h) |
| [Create an Interactive Roadmap Web App on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-mongodb-labs/tree/main/interactive-roadmap) | This is an interesting web application to create interactive roadmap, timeline or milestone graph built with Node.js and React. The backend data store is on MongoDB. In this tutorial, I will show the steps of build and deployment on Alibaba Cloud ECS and MongoDB. | EIP, ECS, MongoDB | [:clapper:](https://www.youtube.com/watch?v=qhP6CMX2sYc) | |
| [Create a Social Web App with Next.js and MongoDB on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-mongodb-labs/tree/main/nextjs-mongodb-app) | This is an Next.js and MongoDB social web application, designed with simplicity for learning and real-world applicability in mind with Next.js and MongoDB on cloud. | EIP, ECS, MongoDB | [:clapper:](https://www.youtube.com/watch?v=ZLoxhny3TeY) | |
| [Create an E-Commerce Web App with Node.js Express Framework and MongoDB on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-mongodb-labs/tree/main/e-commerce-application) | This is a demo E-Commerce online store web application that is built with Node.js Express framework. The backend data store is on MongoDB. In this tutorial, I will show the steps of build and deployment on Alibaba Cloud ECS and MongoDB. | EIP, ECS, MongoDB | [:clapper:](https://www.youtube.com/watch?v=s-j0VSQRBfs) | |
| [Creating a Web Game Map App Using Leaflet, PostgreSQL/PostGIS and Redis on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-interactive-game-map-postgis-redis) | Demo of building game map on Alibaba Cloud: An interactive "Game of Thrones" map powered by Leaflet, PostgreSQL/PostGIS, and Redis. | EIP, ECS, RDS PostgreSQL, Redis | | |
| [Deploy Application Stack Parse Server with MongoDB on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-applicationstack-parse/tree/main/parse-server-mongodb) | Install and deploy Parse Server with MongoDB on Alibaba Cloud. | EIP, ECS, MongoDB | | |
| [Deploy Application Stack Parse Server with RDS for PostgreSQL on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-applicationstack-parse/tree/main/parse-server-postgresql) | Install and deploy Parse Server with RDS for PostgreSQL on Alibaba Cloud. | EIP, ECS, RDS PostgreSQL | | |

# Database solution guide on Alibaba Cloud

- [Oracle Database Migration](https://www.alibabacloud.com/solutions/oracle-database-migration)
  
  Migrate your legacy Oracle databases to Alibaba Cloud to save on long-term costs and take advantage of improved scalability, reliability, robust security, high performance, and cloud-native features.

- [Comprehensive Database Migration](https://www.alibabacloud.com/solutions/database_migration)
  
  Explore Alibaba Cloud's portfolio of fully managed database services, and learn how to leverage a rich set of utility tools and professional database expert services to migrate your business without down time.

- [Cloud Database Solutions for FinTech](https://www.alibabacloud.com/solutions/database-for-fintech)
  
  To know how cloud databases are used to help Fintech users build their business faster and improve the availability of the system.

- [Cloud Database Solutions for Gaming](https://www.alibabacloud.com/solutions/database-for-gaming)
  
  See how advanced cloud database can help users in Gaming industrial to meet all the requirements for high throughput with low latency, and even better than their peers.

- [Database Security](https://www.alibabacloud.com/solutions/database-security)
  
  Protect, backup, and restore your data assets on the cloud with Alibaba Cloud database services.

# Alibaba Cloud Database (ApsaraDB) Logos

| Database Service | Logo |
| :--------------: | :--: |
| RDS (RDS family including RDS for MySQL, RDS for PostgreSQL and RDS for SQL Server)) | ![image.png](https://github.com/alibabacloud-howto/database/raw/main/apsaradb-logos/rds-32.png) |
| RDS for MySQL |  |
| RDS for PostgreSQL |  |
| RDS for SQL Server |  |
| PolarDB (PolarDB family including PolarDB for MySQL, PolarDB for PostgreSQL, PolarDB for Oracle and PolarDB-X)) |  |
| Redis |  |
| Tair (Enhanced Edition of Redis) |  |
| MongoDB |  |
| Lindorm |  |

Logo files in 16, 32, 64 and 128 dimensions: https://github.com/alibabacloud-howto/database/tree/main/apsaradb-logos