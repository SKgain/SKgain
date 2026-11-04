<!-- README.md -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
  <img alt="Saikat Kumar Gain, backend engineer. Animated diagram of events flowing through an API gateway, Kafka, a WebFlux service and Neo4j." src="assets/hero-dark.svg" width="100%">
</picture>

<p>
  <a href="https://www.linkedin.com/in/saikat-kumar-gain-b059422b0/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-161B22?style=flat-square&logo=linkedin&logoColor=6DB33F"></a>
  <a href="mailto:saikatgain.cse@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-161B22?style=flat-square&logo=gmail&logoColor=6DB33F"></a>
  <a href="https://leetcode.com/u/skgain/"><img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-161B22?style=flat-square&logo=leetcode&logoColor=6DB33F"></a>
  <a href="https://codeforces.com/profile/saikatgain630"><img alt="Codeforces" src="https://img.shields.io/badge/Codeforces-161B22?style=flat-square&logo=codeforces&logoColor=6DB33F"></a>
</p>

I build non-blocking microservices with **Spring WebFlux**, **Kafka** and **Neo4j** at **Dhrubok Infotech Service Ltd**. I care about event-driven architecture, clean API contracts, and code that keeps working under load.

## Stack

**Core** &nbsp;
![Java](https://img.shields.io/badge/Java-161B22?style=flat-square&logo=openjdk&logoColor=6DB33F)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-161B22?style=flat-square&logo=springboot&logoColor=6DB33F)
![Spring WebFlux](https://img.shields.io/badge/WebFlux-161B22?style=flat-square&logo=spring&logoColor=6DB33F)
![Spring Security](https://img.shields.io/badge/Spring_Security-161B22?style=flat-square&logo=springsecurity&logoColor=6DB33F)
![Hibernate](https://img.shields.io/badge/Hibernate-161B22?style=flat-square&logo=hibernate&logoColor=6DB33F)

**Data** &nbsp;
![Neo4j](https://img.shields.io/badge/Neo4j-161B22?style=flat-square&logo=neo4j&logoColor=6DB33F)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=6DB33F)
![MySQL](https://img.shields.io/badge/MySQL-161B22?style=flat-square&logo=mysql&logoColor=6DB33F)
![Redis](https://img.shields.io/badge/Redis-161B22?style=flat-square&logo=redis&logoColor=6DB33F)

**Events** &nbsp;
![Kafka](https://img.shields.io/badge/Apache_Kafka-161B22?style=flat-square&logo=apachekafka&logoColor=6DB33F)
![Firebase](https://img.shields.io/badge/Firebase-161B22?style=flat-square&logo=firebase&logoColor=6DB33F)

**Tooling** &nbsp;
![Docker](https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=6DB33F)
![Maven](https://img.shields.io/badge/Maven-161B22?style=flat-square&logo=apachemaven&logoColor=6DB33F)
![Git](https://img.shields.io/badge/Git-161B22?style=flat-square&logo=git&logoColor=6DB33F)
![Postman](https://img.shields.io/badge/Postman-161B22?style=flat-square&logo=postman&logoColor=6DB33F)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-161B22?style=flat-square&logo=intellijidea&logoColor=6DB33F)

## Selected work

### [Quickart](https://github.com/SKgain/quickart-backend)
E-commerce backend split into 9 independently deployable services, with JWT auth at the gateway and Kafka between services.
<br><sub>Java 21, Spring Cloud, Kafka, Neo4j, Eureka, Config Server</sub>

<details>
<summary>Architecture</summary>

```mermaid
flowchart LR
    C[Client] --> G[API Gateway<br/>JWT auth]
    G --> S[Domain services<br/>9 in total]
    S <--> K[(Kafka)]
    S -.registers.-> E[Eureka]
    S -.config.-> CF[Config Server]
```

</details>

### [TaskMaster](https://github.com/SKgain/taskmaster-backend)
Project management backend with role-based access, real-time WebSocket chat, Gemini-generated tasks and analytics dashboards.
<br><sub>Java 21, Spring Boot, PostgreSQL, Docker</sub>

### [BanglaBERT Semantic Similarity API](https://github.com/SKgain/semantic-similarity-backend)
My thesis: Spring Boot serves a fine-tuned BanglaBERT model that rates Bangla sentence pairs as high, moderate or low similarity.
<br><sub>Java, Spring Boot, Python, Docker</sub>

## Publications

| Paper | Venue |
|---|---|
| Bangla Semantic Analysis Using a Transformer-Based BanglaBERT Model | Conference |
| Explainable Stacking Machine Learning Ensemble Model for Liver Disease Prediction | Conference |
| Stroke Prediction Using Ensemble Machine and Deep Learning Models | Q2 journal |

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SKgain/SKgain/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SKgain/SKgain/output/snake-light.svg">
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/SKgain/SKgain/output/snake-light.svg" width="100%">
</picture>

<sub>BSc in Computer Science and Engineering, IUBAT. Based in Dhaka, Bangladesh. Reach me at saikatgain.cse@gmail.com.</sub>
