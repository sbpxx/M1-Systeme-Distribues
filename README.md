# M1-Systeme-Distribues

> Distributed systems with Akka / Java / Maven — M1 university project.

## Description

**Distributed systems project** built in M1 using the **Akka** actor framework and Java. It explores core distributed systems concepts: concurrency, actor-based communication and fault tolerance.

## Repository structure

```
Akka/           # Akka implementation (actors, messages, etc.)
RAPPORT_SD.pdf  # Project report
```

## Tech stack

| Technology | Usage |
|---|---|
| Java | Main language |
| Apache Maven | Build & dependency management |
| Akka | Actor framework for distributed systems |

## Requirements

- JDK 11+
- [Maven](https://maven.apache.org/) installed

## Build & run

```bash
cd Akka
mvn compile
mvn exec:java -Dexec.mainClass="sd.akka.App"
```

## Author

**Sid Ali** — Université de Bourgogne, M1
