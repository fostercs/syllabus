# JS 101

## Summary
CS Fundamentals in JS

## Getting Started

### Username
- Find a unique username that is available across all relevant services.

#### Create the following free accounts
- gmail.com
- github.com

### localhost

#### Chromebook (Pick One)
- repl.it
- stackblitz.com
- glitch.com

#### Windows
- Install Docker

#### macOS
- Install Docker

## Programming Concepts (10 pts)

## Problem Solving
- [Daily Warmups](https://github.com/fostercs/JS101/blob/main/101%2Fwarmup.js)
- [Working with Arrays](https://github.com/fostercs/JS101/blob/main/data/array-ops.js)
- Working with Objects

## Introduction to Concepts
- Math Operations
- Arrays
- Strings
- Binary Search
- Bit-Manipulation (Bitwise)
- Pointers
- Recursion
- Hashing
- Sorting
- Stacks
- Queues
- Linked Lists
- Trees
- Tries
- Heap
- Backtracking
- Greedy
- Dynamic Programming
- Graphs
- Databases
- Objects

# Introduction to Data Structures & Algorithms (20 pts)
- [Algorithm Visualizer](https://algorithm-visualizer.org/)
- [Data Structures & Algorithms](https://github.com/fostercs/dsa-cs-js)
- [JS Algorithms](https://github.com/fostercs/JS101/tree/main/algorithms)
- [Immutability](https://github.com/fostercs/JS101/tree/main/data)

## Assessments
- [Largest num in array](https://github.com/fostercs/JS101/blob/main/assessments/largest-number-in-array.js)
- [Is a palindrome](https://github.com/fostercs/JS101/blob/main/puzzles/is-a-palindrome.md)
- [Largest branch in binary tree](https://github.com/fostercs/JS101/tree/main/assessments/binary-tree-largest-branch)

# Docker 101

[Install Docker - Start Here](https://github.com/fostercs/docker101)

## OSI
- Physical Layer
  - OS
  - Disk
  - Memory
  - CPU
- Data Link Layer
  - DB
- Network Layer (Layer 3)
  - IP Address
- Transport (Layer 4)
  - TCP/IP
- Session
- Presentation
- Application (Layer 7)
  - HTTP

### Assessment
- Weekly contests to gauge conceptual understanding and problem-solving abilities
- Particular focus on complex topics like Dynamic Programming and Graphs (e.g., traversals, shortest paths, etc.)

#### Run Python in a Docker Container locally
```
docker run -it python:3.8
```

# Programming Languages

## JS
- [JS101](https://github.com/fostercs/JS101)
- [ES6 Foundations](https://github.com/fostercs/es6-foundations)
- Map, Filter, Reduce
- [Transducers](https://raganwald.com/2017/04/30/transducers.html)
- Unit Tests

## GO
- [GO101](https://github.com/fostercs/GO101)
- Go Test

# Specalization (5 pts)

## Backend

- MVC
- REST APIs
- ORM
- SpringBoot
- Views
- Database Indexes
- Multithreading

## Full-Stack

Become a Javascript expert which will enable you to excel in any role.

- Building a server, Intro to MVC
- Web architecture, HTML, CSS, Javascript
- Node.js, Backend Architecture, MongoDB, React/Redux

## Data Engineering (Specalization)

- Intro to Data Engineering
- Building efficient Data Processing Systems
- Advanced SQL
- Cloud Services
- Cloud Agnostic
- AWS, GCP, and Azure pros/cons
- Developing ETL pipelines
- Map-Filter-Reduce
- ELK
- Big Data
- Hadoop
- Kafka
- Spark
- Data Warehousing
- Data Modeling
- OLAP
- Dashboarding
- AWS/GCP Deployment
- Workflow Orchestration
- Apache Airflow
- Logging
- Monitoring

- Focus on building foundational skills that will enable you to solve all
 the major problems pertaining to data storage and management.
 - Understand the complexities of developing end-to-end pipelines with
 hands-on experience.

### Assessment
- Capstone Project (Backend, Full-stack, Data engineering)

# Design (10 pts)

## Low Level Design

- [OOP](https://github.com/mhackersu/ninety-nine-bottles-js)
- UML
- Schema Design
- Architecture
  - Microservices
    - [Sidecar](https://github.com/fostercs/JS101/blob/main/design-patterns/structural/sidecar-pattern-structural-declarative.md) - The Sidecar pattern is used to augment the functionality of a microservice by running additional processes or services in the same deployment unit (like a container or pod). This allows for modularization of concerns such as logging, monitoring, configuration, and communication.
- Design Principles (SOLID, Gang of Four)
- SOLID
- GoF
- Orthogonally - A concept where components or systems are designed in such a way that changes in one do not affect others. It emphasizes minimizing dependencies between components to increase modularity and reduce the risk of side effects.
  - Dependency Management
  - Inversion of Control (IoC)
  - [Dependency Injection](https://github.com/fostercs/JS101/blob/main/design-patterns/creational/dependency-injection-creational-imperative-declara) - Dependency Injection promotes orthogonality by reducing the dependencies between components. By injecting dependencies into a class rather than having the class instantiate them itself, DI decouples the class from its dependencies, making it easier to change one without affecting the other. This promotes a more modular and maintainable system, which aligns with the principles of orthogonality.
  - Coupling
  - Cohesion
### Design Patterns
- Creational
  - [**Factory Method**](https://github.com/fostercs/JS101/blob/main/design-patterns/creational/factory-pattern-creational-imperative.md)
  - [**Singleton**](https://github.com/fostercs/JS101/blob/main/design-patterns/creational/singleton-pattern-creational-imperative.md)
  - [**Builder**](https://github.com/fostercs/JS101/blob/main/design-patterns/creational/builder-pattern-creational-imperative.md)
  - Abstract Factory
  - Prototype
- Structural
  - [**Adapter**](https://github.com/fostercs/JS101/blob/main/design-patterns/structural/adapter-pattern-structural-imperative.md)
  - [**Facade**](https://github.com/fostercs/JS101/blob/main/design-patterns/structural/facade-pattern-structural-imperative.md)
  - [**Decorator**](https://github.com/fostercs/JS101/blob/main/design-patterns/structural/decorator-pattern-structural-imperative.md)
  - Bridge
  - Composite
  - Proxy
  - Flyweight
- Behavioral
  - [**Command**](https://github.com/fostercs/JS101/blob/main/design-patterns/behavioral/command-pattern-behavioral-imperative.md)
  - [**Observer**](https://github.com/fostercs/JS101/blob/main/design-patterns/behavioral/observer-pattern-behavioral-imperative.md)
  - [**Strategy**](https://github.com/fostercs/JS101/blob/main/design-patterns/behavioral/strategy-pattern-behavioral-imperative.md)
  - Interpreter
  - Chain of Responsibility
  - Iterator
  - Mediator
  - Memento
  - State
  - Template Method
  - Visitor

### Real-World Design (Low-Level)
- Movie Ticket Booking System
- Expense Sharing Application
- Distributed Cache
- Parking Lot

## Assesment & Objective
- Real-world case studies and examples on large scale open source repositories
- Hands-on working code implementation in class for every case study
- TA Driven Code Reviews and Assignments
- Detailed discussions on Schema Designs, Design Principles and Practices

## High Level Design
- Scaling (Horizontal vs Vertical)
- DNS Lookup/DNS Servers
- Load Balancer
- Consistent Hashing
- Caching and CDN
- CAP Theorem
- Master-Slave
- Multi-Master
- SQL vs NoSQL DB
- Zookeeper + Kafka
- Quad Trees
- Monoliths & Microservices

### Real-World Design (High-Level)
- Search Typehead
- Search Engine (Google)
- Social Chat (Messenger)
- Social KB (Quora)
- Distribuited Crawler
- Video Streaming Platform
- Train Ticket Booking System

### Complex systems
- Cassandra DB
- Distributed File Systems

# Containers
- [Docker101](https://github.com/fostercs/docker101)

# Integration Tests
- Swagger
- Scaling secrets

# CI
- Linting with Git Hooks

# Web3
- [React Server Components](https://www.joshwcomeau.com/react/server-components/)
- [RSC Demo](https://vercel.com/new/bfsio-projects/templates/next.js/react-server-components-notes-demo)
- [Institute of Free Technology](https://free.technology)
- [Smart Conracts in Solidity](https://docs.soliditylang.org/en/latest/introduction-to-smart-contracts.html)

# Reference
- [Glossary](glossary.md)
- [UX Terminology](ux.md)
- [Gitlab Handbook](https://handbook.gitlab.com/handbook)
