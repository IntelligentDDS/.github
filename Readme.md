# IntelligentDDS: Intelligent Digital Delivery Systems

Welcome to **IntelligentDDS**! We are an open-source research group. Our work focuses on leveraging AI, Machine Learning, and Data Mining to solve reliability, performance, and scalability challenges in modern distributed systems.

## 🔍 Project Index & Classification

### 1. Anomaly Detection (AD)

Frameworks that utilize deep learning and statistical methods to detect irregularities in metrics, logs, and traces.

* **[SwissLog](https://github.com/IntelligentDDS/SwissLog)**: A deep learning-based framework for log-based anomaly detection (ISSRE'20 / TDSC'22).
* **[ShareAD](https://github.com/IntelligentDDS/ShareAD)**: A "Pre-train and Align" framework for modern online system anomaly detection (TOSEM 2025).
* **[Uni-AD](https://github.com/IntelligentDDS/Uni-AD)**: Unified approaches for multi-dimensional metric and topology-aware detection.

### 2. Root Cause Analysis (RCA) & Incident Management

Tools for localizing failure origins and managing the lifecycle of system incidents.

* **[MicroRank](https://github.com/IntelligentDDS/MicroRank)**: End-to-end latency fault localization in microservices using extended spectrum analysis (WWW'21).
* **[GEM](https://github.com/IntelligentDDS/GEM)**: An evolution-aware framework treating subgraphs as first-class citizens for incident management (TSE 2025).
* **[ProfRCA](https://github.com/IntelligentDDS/ProfRCA)**: Fine-grained RCA combining continuous profiling data with Large Language Models (LLMs) (SANER 2026).

### 3. Observability & Data Optimization

Optimizing the collection, storage, and processing of high-volume telemetry data.

* **[LogReducer](https://github.com/IntelligentDDS/LogReducer)**: High-efficiency log compression and redundancy elimination.
* **[LogShrink](https://github.com/IntelligentDDS/LogShrink)**: Specialized tools for reducing log volume while preserving diagnostic utility.

### 4. Advanced Log Intelligence (LogGen, LogFun, LogBoost)

This specialized suite focuses on the lifecycle of system logs—from generation and parsing to quality enhancement for downstream AIOps tasks.

* **[LogGen](https://github.com/IntelligentDDS/LogGen)**: An automated log generation framework designed to synthesize realistic logs for testing and training without compromising sensitive data (ICSE'23).
* **[LogFun](https://github.com/IntelligentDDS/LogFun)**: A logic-level log parsing approach that focuses on the functional structure of log messages to improve template extraction accuracy (FSE'24).
* **[LogBoost](https://github.com/IntelligentDDS/LogBoost)**: A framework designed to "boost" the quality of raw logs, making them more suitable for automated anomaly detection and root cause analysis.

### 5. Benchmarks & Resources

* **[Augmented-TrainTicket](https://github.com/IntelligentDDS/Augmented-TrainTicket)**: An enhanced version of the TrainTicket microservice benchmark with advanced fault injection.
* **[Awesome-Papers](https://github.com/IntelligentDDS/awesome-papers)**: A curated list of top-tier papers (ICSE, FSE, ASE, ISSTA, etc.) regarding Cloud Computing and AIOps.

---

## 🛠 Tech Stack

* **Languages**: Python, Go, Java, C#
* **Infrastructure**: Kubernetes, Prometheus, Istio, gRPC
* **AI Techniques**: Large Language Models (LLMs), Graph Neural Networks (GNN), Transformer, Reinforcement Learning (RL)
