# Real Time Analytic With Druid - Airflow - Kafka - Superset
[![Kafka](https://img.shields.io/badge/kafka-5.2.0-green)](https://kafka.apache.org/documentation/)
[![Airflow](https://img.shields.io/badge/airflow-2.2.4-green)](https://airflow.apache.org/docs/)
[![Druid](https://img.shields.io/badge/druid-0.22.1-orange)](https://druid.apache.org/docs/latest/design/)
[![Redis](https://img.shields.io/badge/redis-6.2.6-orange)](https://redis.io/)
[![Posgresql](https://img.shields.io/badge/postgres-14.1-brown)](https://www.postgresql.org/)
[![Superset](https://img.shields.io/badge/Superset-0.63-lightgrey)](https://superset.apache.org/docs/intro/)

In today's world you want to learn from your customers as quickly as possible. This blog gives an introduction to setting up streaming analytics using open source technologies. We'll use Apache {Kafka, Superset, Druid, Airflow} to set up a system that allows you to get a deeper understanding of the behaviour of your customers. Having your analytics in a streaming fashion enable you to continuously analyze your customer's behaviour and act on it. For example:

 - When we perform a new experiment using A/B testing, we want to monitor the experiment and have the possibility to terminate either experiment A or B early, if the results show that one significantly outperforms the other.
 - All the actions of users on your online website tell something about their intent. When we have the ability to process the data immediately, we can tailor the content to each user.
 - Gather general information about the usage of the application to align your next iterations of the application. :fire: :fire: :fire: :fire:

## Screenshots & Gifs

**View System**

<div>
    <kbd>
        <img title="View System" src="https://github.com/apot-group/document-processing/blob/main/o-statics/images/server.png?raw=true" />
    </kbd>
    <br/>
</div>
<br>

## Contents
- [Screenshots & Gifs](#screenshots--gifs)
- [Example](#example)
    - [1. Install docker, docker-compose](https://github.com/apot-group/document-processing/tree/main/dp-api/README.md#1-login-accept-token)
    - [2. Pull git repo](https://github.com/apot-group/document-processing/tree/main/dp-api/README.md#2-login-refresh-token)
    - [3. Start Server](https://github.com/apot-group/document-processing/tree/main/dp-api/README.md#3-ml-predict)
- [Contact Us](#contact-us)


## Example

### 1. Install docker and docker-compose

`https://www.docker.com/`

### 2. Pull git repo
`git clone https://github.com/apot-group/real-time-analytic.git` 

### 3. Start Server
`cd real-time-analytic && docker-compose up`


| Service               | URL                              |
| :-------------------: | :------------------------------: |
| Druid Unified Console | http://localhost:8888/           |
| Druid Legacy Console  | http://localhost:8081/           |
| Superset              | http://localhost:8088/           |
| Airflow               | http://localhost:3000/           |


## Contact Us
- Email-1: duynnguyenngoc@hotmail.com - Duy Nguyen :heart: :heart: :heart: 