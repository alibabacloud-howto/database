<!--
 * @Author: your name
 * @Date: 2021-06-17 10:55:38
 * @LastEditTime: 2021-08-16 10:58:54
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /ws_cloudsolution/database/README.md
-->
# Database centric cloud solution on Alibaba Cloud

| Solution | Description | Related Cloud Services | Video Tutorial | Solution Page on Alibaba Cloud |
| :------: | :---------: | :--------------------: | :------------: | :----------------------------: |
| [Cloud Native WordPress on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-cloud-native-web-hosting) | Quick start with Wordpress on Alibaba Cloud with cloud native features such as high availability, auto-scaling, etc. | EIP, SLB, ECS, ESS, Redis, PolarDB MySQL | [:clapper: Part 1](https://www.youtube.com/watch?v=TnWaGHBxPuw) [:clapper: Part 2](https://www.youtube.com/watch?v=POQ_nxjnIYM) | [:beginner:](https://www.alibabacloud.com/architecture/solution-implementation/building-auto-scaling-wordpress-website-on-alibaba-cloud) |
| [WordPress (Marketplace) on Alibaba Cloud](https://github.com/alibabacloud-howto/solution-marketplace-wordpress) | Quick start with Wordpress (Marketplace image) on Alibaba Cloud with different levels of service combination with price estimation. | EIP, SLB, ECS, ESS, Redis, RDS MySQL, PolarDB MySQL |  |  |
| [Scoreboard of Rose Bowl Games powdered by Redis & MySQL - Use Terraform To Provision All Resources](https://github.com/alibabacloud-howto/solution-mysql-redis-cache-simple) | The simplest solution for RDS MySQL database caching with Redis. This solution relies on the expiration time (TTL) of the key in Redis. Redis will not be updated proactively when MySQL is updated. This approach is simple to implement, but the inconsistency duration may be very long especially for the scenario that the read request is very frequent and the expiration time is relatively long, a lot of long-term dirty data will be generated. | ECS, Redis, RDS MySQL | [:clapper:](https://www.youtube.com/watch?v=POQ_nxjnIYM) | [:beginner:](https://www.alibabacloud.com/architecture/solution-mysql-redis-cache-simple) |
| [Redis Data Synchronization with RDS MySQL Using Canal & Kafka](https://github.com/alibabacloud-howto/solution-mysql-redis-canal-kafka-sync) | This solution uses Kafka and Canal to achieve data synchronization between RDS MySQL and Redis. | ECS, RDS MySQL, Redis, Kafka, Canal | [:clapper:](https://www.youtube.com/watch?v=O-GoA6182mI) | [:beginner:](https://www.alibabacloud.com/architecture/solution-mysql-redis-canal-kafka-sync) |
| [Deploy MongoDB Instances in Multiple Regions Automatically Using Terraform](https://github.com/alibabacloud-howto/solution-mongodb-multiregion-sync) | Using MongoShake deployed on ECS to one-way synchronize 2 MongoDB deployed in 2 regions respectively. | ECS, MongoDB, MongoShake | [:clapper:](https://www.youtube.com/watch?v=k6zUZcw6CU4) | |
| [Create Online Game Leaderboard on Redis](https://github.com/alibabacloud-howto/solution-online-leaderboard-redis) | Leaderboard sample for Gaming on cloud. This sample contains the Terraform scripts to provision an ECS and a Redis instance on Alibaba Cloud region, also there is a sample for setting up Java development environment on ECS and running a Leaderboard. | ECS, Redis | [:clapper:](https://www.youtube.com/watch?v=LMsMqYz9ik8) | |
| [Cloud Native Web App on Alibaba Cloud: COVID-19 Tracker](https://github.com/alibabacloud-howto/solution-covid19-tracker) | Deploy simple cloud native web app on Alibaba Cloud to visualize the spread and impact of Covid-19, subscribe for daily updates, and view stats. | EIP, ECS, RDS MySQL | | |
| [Deploy and Run Netflix Dispatch on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/netflix_dispatch) | Running open source project Netflix Dispatch on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). | EIP, ECS, RDS PostgreSQL | | |
| [Deploy and Run Apache Superset on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/apache-superset) | Running open source project Apache Superset on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). | EIP, ECS, RDS PostgreSQL | | |
| [Deploy and Run Redash on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/redash) | Running open source project Redash on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). | EIP, ECS, RDS PostgreSQL | | |
| [Deploy and Run Apache OFBiz on Alibaba Cloud](https://github.com/alibabacloud-howto/opensource_with_apsaradb/tree/main/apache-ofbiz) | Running open source project Apache OFBiz on Alibaba Cloud with ApsaraDB (Alibaba Cloud Database). | EIP, ECS, RDS MySQL | | |
| [Running TPC-H benchmark on AnalyticDB PostgreSQL](https://github.com/alibabacloud-howto/solution-adbpg-labs/tree/master/benchmark-tpc-h) | The full steps of generating TPC-H data set and running TPC-H 22 queries on AnalyticDB PostgreSQL. | EIP, ECS, OSS, AnalyticDB PostgreSQL | [:clapper:](https://www.youtube.com/watch?v=yR3jVBQkrzU) | |