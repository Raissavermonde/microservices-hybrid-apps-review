# microservices-hybrid-apps-review
Extraction data from bibliographic review on microservices in hybrid applications
# Bibliographic Review: Microservices in Hybrid Applications

Replication package for the paper submitted to **SBES 2026 — Track on Innovative Ideas and Emerging Results (IIER)**:

> *Technologies and Approaches for Microservices Development in Hybrid Applications: A Bibliographic Review*

This repository contains the extraction data, selection criteria, and study classification used in the review. The goal is to support transparency and reproducibility of the results reported in the paper.

---

## Research Questions

| ID | Question |
|----|----------|
| RQ1 | Which technologies and approaches have been used for microservices development in hybrid applications? |
| RQ2 | Which architectures and methods are employed in building microservices-based applications? |
| RQ3 | Which programming languages, tools, or frameworks are most commonly used in this context? |

---

## Search Protocol

**Databases searched:** SBC OpenLib · Google Scholar · IEEE Xplore · ACM Digital Library · Scopus

**Search strings:**
- Portuguese: `(microsserviços OR serviços) AND desenvolvimento AND "aplicações híbridas"`
- English: `(microservices OR services) AND development AND "hybrid applications"`

**Publication period:** 2022–2026

**Inclusion criteria**

| ID | Criterion |
|----|-----------|
| IC1 | Published between 2022 and 2026 |
| IC2 | Primary study |
| IC3 | Addresses technologies, methods, or tools for microservices development |
| IC4 | Full text available in the searched database |

**Exclusion criteria**

| ID | Criterion |
|----|-----------|
| EC1 | Duplicate across databases |
| EC2 | Outside the defined publication period |
| EC3 | Does not address microservices or services development |
| EC4 | Full text not accessible |

---

## Selected Studies

A total of 20 studies were selected and coded E1–E20.

| ID | Title | Year | Source |
|----|-------|------|--------|
| E1 | MoocFlix: A Microservices-Based Architecture for Scalable and Efficient MOOC Streaming Platforms | 2025 | IEEE |
| E2 | An Intelligent Hybrid Mobile Application Architecture Integrating Cloud Based Generative AI Services | 2025 | Google Scholar |
| E3 | Dynamic Analysis for Detecting Microservices Antipatterns | 2025 | SBC |
| E4 | Modernização de Arquitetura de Sistemas: Uma abordagem para transformação digital no sistema financeiro | 2024 | SBC |
| E5 | SP2Mic: Uma ferramenta para geração de código de microsserviços a partir de stored procedures | 2024 | SBC |
| E6 | JS-Distributor: Decomposing Monolith Applications into Microservices | 2025 | SBC |
| E7 | Processo de Migração de Aplicação Mainframe Cobol para Microsserviços Java na Nuvem | 2024 | SBC |
| E8 | Distributed Healthcare Information System Based on High-Concurrency Microservice Architecture | 2023 | IEEE |
| E9 | RM2MS: A Tool for Automatic Identification of Microservices from Requirements Models | 2023 | IEEE |
| E10 | Migration of Monolithic Systems to Microservices using AI: A Systematic Mapping Study | 2024 | SBC |
| E11 | A Real-time Data Synchronization Approach for High-availability Micro Applications | 2025 | SBC |
| E12 | SPL Integrated with Microservices: A Hybrid Architectural Proposal for Multitenant SaaS | 2023 | SBC |
| E13 | Agentic AI for Microservices: Autonomous Optimization of High-Volume Financial Transactions in Cloud Native Environments | 2025 | IEEE |
| E14 | M2FaaS: Transparent and Fault Tolerant FaaSification of Node.js Monolith Code Blocks | 2022 | Scopus |
| E15 | Plataforma SobreVidas: Solução Tecnológica para o Rastreamento e Monitoramento Contínuo na APS | 2024 | SBC |
| E16 | An Efficient Microservices Architecture for MLOps | 2023 | IEEE |
| E17 | Towards Migrating Legacy Software Systems to Microservice-based Architectures | 2022 | IEEE |
| E18 | Implementing a PHP API Gateway Based on Microservices Architecture | 2024 | IEEE |
| E19 | RapidMS: A Tool for Supporting Rapid Microservices Generation and Refinement from Requirements Model | 2021 | IEEE |
| E20 | Low-Coupling and High-Cohesion Microservice Partitioning Method to Support Rapid Development of Steel Industry Management Systems | 2024 | IEEE |

---

## Extraction Results

### RQ1 — Technologies and Concepts

| Technology / Concept | Studies |
|----------------------|---------|
| Microservices Architecture | E1–E9, E12, E13, E15, E16, E19 |
| Cloud-Native / Distributed Systems | E1, E3, E4, E8, E13, E16 |
| Cloud Computing / Serverless | E2, E7, E13, E14 |
| Containerization (Docker) | E1, E4, E6, E15 |
| Orchestration (Kubernetes) | E1, E3, E4, E13 |
| Message Brokers (Kafka / RabbitMQ) | E1, E4, E6, E8, E11, E15 |
| API Gateway | E2, E5, E12, E15, E16, E18 |
| AI / Machine Learning | E2, E7, E9, E10, E13, E15 |
| Generative AI | E2, E7, E13, E15 |
| Domain-Driven Design (DDD) | E12, E19, E20 |
| CI/CD and DevOps | E3, E4, E16 |
| Model-Driven Engineering | E9, E19 |
| FaaS / Serverless Functions | E14 |

### RQ2 — Research Methods

| Method | Count | Studies |
|--------|-------|---------|
| Experimental / with evaluation | 9 | E1, E3, E5, E6, E7, E8, E13, E18, E19 |
| Architectural Proposal | 8 | E2, E9, E11, E12, E15, E16, E19, E20 |
| Case Study | 5 | E9, E12, E17, E19, E20 |
| ML / Evolutionary Algorithms | 4 | E9, E10, E13, E17 |

### RQ3 — Programming Languages and Tools

| Language / Framework | Count | Studies |
|----------------------|-------|---------|
| Java / Spring Boot | 10 | E1, E5–E9, E11, E17, E19, E20 |
| JavaScript / Node.js / TypeScript | 6 | E1, E4, E6, E11, E14, E15 |
| Python | 3 | E3, E4, E13 |
| C# / .NET | 2 | E4, E5 |
| Kotlin | 1 | E15 |
| PHP | 1 | E18 |
| Dart (Flutter) | 1 | E2 |
| UML / OCL (model-driven) | 2 | E9, E19 |

### Generative AI Usage

| Study | Tool / Approach |
|-------|----------------|
| E2 | LLMs for text and image generation via cloud-based GenAI services |
| E7 | ChatGPT for automatic COBOL→Java transpilation |
| E13 | Agentic AI with Deep Q-Network (DQN) for autonomous optimization |
| E15 | LLMs + Retrieval-Augmented Generation (RAG) for clinical decision support |

### Study Context

| Context | Studies |
|---------|---------|
| Academic | E1, E3, E4, E6, E7, E8, E9, E10, E12, E13, E14, E15, E16, E17, E18, E19, E20 |
| Academic + Industry partnership | E5, E11 |
| Corporate | E2 |

---

## Artifact Availability

All selected studies were retrieved from publicly accessible databases. The extraction protocol, inclusion/exclusion criteria, and classification data presented here are intended to support the review process. Requests for additional information can be directed to the authors via the paper submission system. 
