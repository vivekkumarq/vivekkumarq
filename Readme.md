<h1 align="center">Vivek Kumar</h1>

<p align="center">
  <b>Software Engineer</b> · Java Backend · Spring Boot · Microservices<br>
  Bengaluru, India
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vivek-k-87036b104/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:vkumar.vivek222@gmail.com"><img src="https://img.shields.io/badge/Email-vkumar.vivek222@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open%20to-Backend%20Roles-2ea44f?style=flat-square" alt="Open to backend roles">
</p>

---

### About

Software Engineer with **3+ years** building scalable backend microservices in **Java, Spring Boot, Quarkus and Kubernetes**. I work on enterprise telecom platforms at Netcracker, where the services I own run in high-traffic production environments and are used by business teams every day.

What I'm good at: designing services that stay clean as they grow — clear API contracts, event-driven boundaries with Kafka, and a real test and CI/CD story behind them. I'm comfortable across the whole lifecycle: low-level design, implementation, code review, deployment, and production support.

- 🏢 **Software Engineer @ Netcracker Technology**, Bengaluru — Sep 2022 to present
- 🏆 **Spotlight of the Month (2025)** for outstanding contribution and value delivery
- 🎓 **B.E. Computer Science**, SJB Institute of Technology — First Class with Distinction, 8.5/10
- 💬 Ask me about GraphQL API design, Kafka event-driven systems, or Kubernetes deployments

---

### What I Work On

**Backend microservices at scale.** Designed and shipped services in Java, Spring Boot, GraphQL and PostgreSQL across enterprise telecom modules — including an Assigned Customers API that aggregates data from multiple services with advanced filtering and sorting.

**API design, REST and GraphQL.** Built GraphQL queries and mutations plus GraphQL-to-REST proxy layers to simplify cross-service integration. Maintained REST APIs for 5+ business modules with full Swagger/OpenAPI documentation used by internal teams and partner services.

**Event-driven architecture.** Implemented Kafka-based asynchronous messaging to decouple downstream services and raise throughput across a distributed system.

**Product platforms.** Contributed to the Customer Insights platform (Tags & Alerts for classifying and monitoring customer activity, in real time) and to the Customer Sales & Representative Dashboard, where I built backend services and designed CIP chains for structured customer-onboarding workflows.

**Production ownership.** Delivered backend features for **Etisalat (Emirates Telecommunications)** using Groovy Script and Quarkus, diagnosing and resolving production issues in high-traffic telecom environments. Integrated Keycloak for role-based access control and improved observability through better logging, error handling and performance monitoring.

**DevOps and delivery.** Containerised and deployed with Docker and Kubernetes through GitLab CI/CD and Jenkins pipelines, cutting deployment time and release failures. Applied clean architecture, design patterns and steady refactoring to modernise legacy modules, working closely with QA, DevOps and Product.

---

### Open Source

**[OpenAPITools/openapi-generator](https://github.com/OpenAPITools/openapi-generator)** · 26.7k stars · merged in [#24810](https://github.com/OpenAPITools/openapi-generator/pull/24810), shipping in 7.26.0

The Kotlin `jaxrs-spec` server generator emitted no documentation for its operations, while the equivalent Java generator had always produced Javadoc. Added a KDoc block driven by the OpenAPI `summary` and `description`, with `@param` and `@return`, matching the conventions already used elsewhere in the Kotlin generator. Fixes [#24794](https://github.com/OpenAPITools/openapi-generator/issues/24794).

**[eclipse-ee4j/yasson](https://github.com/eclipse-ee4j/yasson)** · the Jakarta JSON Binding reference implementation · [#751](https://github.com/eclipse-ee4j/yasson/pull/751), approved and awaiting merge

Records declaring a compact constructor lost the type arguments of their generic components, so a `List<T>` deserialized into a list of maps. Traced it to `Parameter#getParameterizedType()` returning the raw type for mandated parameters on JDK 22, and resolved creator parameter types through `Executable#getGenericParameterTypes()` instead.

**[quarkusio/quarkus](https://github.com/quarkusio/quarkus)** · [#56091](https://github.com/quarkusio/quarkus/issues/56091), diagnosed and closed

Reported as a Quarkus JSON-B bug. Reproduced it against plain Yasson with no framework involved and isolated it to a JDK reflection regression present in 22 but not in 21 or 25, which let the maintainers close it.

---

### Tech Stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Groovy-4298B8?style=for-the-badge&logo=apachegroovy&logoColor=white" alt="Groovy">
</p>

**Frameworks**
<p>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring">
  <img src="https://img.shields.io/badge/Quarkus-4695EB?style=for-the-badge&logo=quarkus&logoColor=white" alt="Quarkus">
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white" alt="Hibernate">
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge" alt="JPA">
  <img src="https://img.shields.io/badge/jOOQ-BB4444?style=for-the-badge" alt="jOOQ">
</p>

**APIs & Messaging**
<p>
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" alt="GraphQL">
  <img src="https://img.shields.io/badge/REST%20APIs-005571?style=for-the-badge" alt="REST APIs">
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka">
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" alt="Swagger">
</p>

**DevOps & Cloud**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab CI/CD">
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins">
  <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white" alt="Keycloak">
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white" alt="FlywayDB">
</p>

**Databases & Testing**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit">
  <img src="https://img.shields.io/badge/Mockito-78A641?style=for-the-badge" alt="Mockito">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman">
</p>

**Concepts** — Microservices · Distributed Systems · Event-Driven Architecture · System Design & LLD · Design Patterns · Clean Architecture · Data Structures & Algorithms · Agile/Scrum

---

### GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=vivekkumarq&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=default" alt="Vivek Kumar's GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vivekkumarq&layout=compact&hide_border=true&langs_count=6&theme=default" alt="Top languages">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=vivekkumarq&hide_border=true" alt="GitHub contribution streak">
</p>

---

### Let's Connect

I'm open to backend and platform engineering roles. The fastest way to reach me is email or LinkedIn.

<p>
  <a href="mailto:vkumar.vivek222@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/vivek-k-87036b104/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>
