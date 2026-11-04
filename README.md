<!-- README.md -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
  <img alt="Saikat Kumar Gain, backend engineer. An event travels through an API gateway, Kafka, a WebFlux service and Neo4j. Now at Dhrubok Infotech, Dhaka." src="assets/hero-dark.svg" width="100%">
</picture>

<p>
  <a href="https://saikatgain.site"><img alt="Portfolio: saikatgain.site" src="assets/btn-portfolio.svg" height="40"></a>
  <a href="https://www.linkedin.com/in/saikat-kumar-gain-b059422b0/"><img alt="LinkedIn" src="assets/btn-linkedin.svg" height="40"></a>
  <a href="mailto:saikatgain.cse@gmail.com"><img alt="Email" src="assets/btn-email.svg" height="40"></a>
  <a href="https://leetcode.com/u/skgain/"><img alt="LeetCode" src="assets/btn-leetcode.svg" height="40"></a>
  <a href="https://codeforces.com/profile/saikatgain630"><img alt="Codeforces" src="assets/btn-codeforces.svg" height="40"></a>
</p>

I build non-blocking microservices with **Spring WebFlux**, **Kafka** and **Neo4j** at **Dhrubok Infotech Service Ltd**. I care about event-driven architecture, clean API contracts, and code that keeps working under load.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stack-light.svg">
  <img alt="Tech stack. Language and framework: Java, Spring Boot, Spring WebFlux, Spring Security, Hibernate. Data: Neo4j, PostgreSQL, MySQL, Redis. Messaging: Apache Kafka, Firebase. Tooling: Docker, Maven, Git, Postman, IntelliJ IDEA." src="assets/stack-dark.svg" width="100%">
</picture>

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
| Ancient Bengal Numismatic Dataset of Vanga Janapada, Gauda, Samatata, and Harikela Coinage | Q1 journal |
| Bangla Semantic Analysis Using a Transformer-Based BanglaBERT Model | Conference |
| Explainable Stacking Machine Learning Ensemble Model for Liver Disease Prediction | Conference |
| Stroke Prediction Using Ensemble Machine and Deep Learning Models | Q2 journal |

## Everything, connected

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/graph-light.svg">
  <img alt="Neo4j-style graph: Saikat works at Dhrubok (WebFlux, Neo4j, Kafka), built Quickart, TaskMaster and a BanglaBERT API, and published four papers." src="assets/graph-dark.svg" width="100%">
</picture>

<sub>BSc in Computer Science and Engineering, IUBAT. Based in Dhaka, Bangladesh. Reach me at saikatgain.cse@gmail.com.</sub>
