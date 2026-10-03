<div align="center">

# Hi, I'm Chakravarthy Batna 👋

<a href="https://github.com/chakravarthyBatna">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=640&lines=Backend+Engineer+%C2%B7+Java+%26+Spring;Open-source+contributor+to+Trino%2C+Quarkus+%26+Camel;I+debug+the+hard+bugs+in+big+codebases" alt="Typing intro" />
</a>

**Backend Software Engineer at [WaveMaker](https://www.wavemaker.com)** · Java · Distributed systems · Databases

[![Trino](https://img.shields.io/badge/Trino-2_PRs_merged-DD00A1?style=flat-square&logo=trino&logoColor=white)](https://github.com/trinodb/trino/pulls?q=is%3Apr+author%3AchakravarthyBatna)
[![Quarkus](https://img.shields.io/badge/Quarkus-contributor-4695EB?style=flat-square&logo=quarkus&logoColor=white)](https://github.com/quarkusio/quarkus/pulls?q=is%3Apr+author%3AchakravarthyBatna)
[![Apache Camel](https://img.shields.io/badge/Apache_Camel-contributor-E97826?style=flat-square&logo=apache&logoColor=white)](https://github.com/apache/camel/pulls?q=is%3Apr+author%3AchakravarthyBatna)

</div>

---

### 🧑‍💻 About me

I'm a backend engineer at **WaveMaker**, a low-code platform that companies use to build enterprise web and mobile apps. I work on the Java / Spring Boot backend of the platform.

- **At work:** I build and maintain backend features, REST APIs, and integrations used by WaveMaker's customers.
- **Debugging:** I'm comfortable opening a large codebase I've never seen and tracing a problem down to its root cause.
- **Open source:** in my free time, I fix bugs in well-known Java projects, reviewed and merged by their maintainers.
- **Currently learning:** system design, building scalable REST APIs, and writing safe concurrent code in Java.

---

### 🌍 Open-source contributions

| Project | Contribution | Status |
| :-- | :-- | :-: |
| <img src="https://github.com/trinodb.png" width="16"/> **Trino** | [Fix corrupted results in `max_by`/`min_by` — flat row/array/map writers left stale null flags when reusing a buffer](https://github.com/trinodb/trino/pull/31345) | ✅ Merged |
| <img src="https://github.com/trinodb.png" width="16"/> **Trino** | [MongoDB connector: report missing tables as *table not found* when case-insensitive matching is off](https://github.com/trinodb/trino/pull/31132) | ✅ Merged |
| <img src="https://github.com/trinodb.png" width="16"/> **Trino** | [Support the `NUMBER` type in SQL/JSON functions (`json_object`, `json_array`, `json_value`)](https://github.com/trinodb/trino/pull/31181) | 🔄 In review |
| <img src="https://github.com/quarkusio.png" width="16"/> **Quarkus** | [Make Brotli4J optional in `quarkus-vertx-http` — it caused `UnsatisfiedLinkError` in apps using Apache HttpClient 5](https://github.com/quarkusio/quarkus/pull/56771) | 🔄 In review |
| <img src="https://github.com/apache.png" width="16"/> **Apache Camel** | [CAMEL-25262: fix `NullPointerException` at route startup when using `xtokenize`](https://github.com/apache/camel/pull/27316) | 🔄 In review |
| <img src="https://github.com/apache.png" width="16"/> **Apache Camel** | [CAMEL-25187: accept media ranges like `application/*` in REST request validation](https://github.com/apache/camel/pull/27315) | 🔄 In review |

<sub>👉 [See all my pull requests](https://github.com/search?q=author%3AchakravarthyBatna+is%3Apr+-user%3AchakravarthyBatna&type=pullrequests)</sub>

---

### 🛠️ Tech stack

**Languages**<br/>
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frameworks**<br/>
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Quarkus](https://img.shields.io/badge/Quarkus-4695EB?style=for-the-badge&logo=quarkus&logoColor=white)
![Apache Camel](https://img.shields.io/badge/Apache_Camel-E97826?style=for-the-badge&logo=apache&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)

**Data**<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=for-the-badge&logo=trino&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Build & DevOps**<br/>
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

### 🔍 How I work

```text
 Bug report ──► Reproduce in isolation ──► Find the root cause in the source
                                                     │
 Merged PR ◄── Clear write-up for maintainers ◄── Smallest fix + tests
```

Example: for the Quarkus Brotli issue, I built a minimal reproducer with only `quarkus-rest` and `httpclient5`, which showed the bug was in Quarkus' dependency scope — not in Camel, where it was first reported.

---

### 📫 Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chakravarthybatna/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/chakravarthybatna/)

<div align="center">
<sub>Open to backend / platform engineering roles.</sub>
</div>
