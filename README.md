# Awesome AIOps

> **Note:** This repository contains an automatically compiled list of frameworks, tools, and resources related to AIOps (Artificial Intelligence for IT Operations).

A curated list of awesome AIOps (Artificial Intelligence for IT Operations) and AIOps-related software.


Table of Contents:
- [AIOps Platforms & Frameworks](#aiops-platforms-&-frameworks)
    - [Full-Stack AIOps Platforms](#full-stack-aiops-platforms) (3)
    - [Intelligent Monitoring Systems](#intelligent-monitoring-systems) (4)
- [Observability & Monitoring](#observability-&-monitoring)
    - [Log Analysis & Intelligence](#log-analysis-&-intelligence) (7)
- [Automation & Orchestration](#automation-&-orchestration)
    - [AI-Powered Automation](#ai-powered-automation) (1)
    - [Self-Healing Systems](#self-healing-systems) (1)
- [Data & Analytics](#data-&-analytics)
    - [Root Cause Analysis](#root-cause-analysis) (3)
    - [Anomaly Detection](#anomaly-detection) (2)
    - [Predictive Maintenance](#predictive-maintenance) (1)
- [DevOps AI Integration](#devops-ai-integration)
    - [Testing Intelligence](#testing-intelligence) (1)
- [Cloud & Infrastructure AI](#cloud-&-infrastructure-ai)
    - [Infrastructure as Code AI](#infrastructure-as-code-ai) (1)
- [Tools & Utilities](#tools-&-utilities)
    - [Visualization & Dashboards](#visualization-&-dashboards) (1)
- [Educational Resources](#educational-resources) (1)



## AIOps Platforms & Frameworks

### Full-Stack AIOps Platforms

- [centreon/centreon](https://github.com/centreon/centreon) (142 PHP) - Centreon is an open-source AIOps platform providing comprehensive monitoring and holistic visibility for complex IT workflows across cloud and edge environments.
- [keephq/keep](https://github.com/keephq/keep) (11463 Python) - Keep is an open-source AIOps and alert management platform that provides a unified interface for alert deduplication, enrichment, correlation, and automation with AI-powered capabilities and extensive integrations.
- [microsoft/AIOpsLab](https://github.com/microsoft/AIOpsLab) (810 Python) - AIOpsLab is a holistic framework for designing, developing, and evaluating autonomous AIOps agents with support for benchmarking, fault injection, and telemetry in cloud environments.

### Intelligent Monitoring Systems

- [Arize-ai/openinference](https://github.com/Arize-ai/openinference) (869 Python) - OpenInference is an OpenTelemetry-based instrumentation framework designed to enhance observability and tracing of AI applications, particularly large language models, to support AI-driven monitoring and debugging in AIOps environments.
- [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix) (8696 Jupyter Notebook) - Phoenix is an open-source AI observability platform for experimentation, evaluation, and troubleshooting of large language model applications, supporting multiple frameworks and deployment environments.
- [lmnr-ai/lmnr](https://github.com/lmnr-ai/lmnr) (2630 TypeScript) - Laminar is an open-source observability platform designed specifically for AI agents, offering tracing, evaluation, monitoring, and data analysis tools to support AI-powered operations and workflows.
- [truera/trulens](https://github.com/truera/trulens) (3121 Python) - TruLens is a tool for systematic evaluation and tracking of large language model experiments and AI agents to improve AI application performance and reliability.

## Observability & Monitoring

### Log Analysis & Intelligence

- [d0ng1ee/logdeep](https://github.com/d0ng1ee/logdeep) (455 Python) - LogDeep is an open-source deep learning-based toolkit for automated anomaly detection in system logs, featuring state-of-the-art models like DeepLog, LogAnomaly, and RobustLog.
- [Jun-jie-Huang/awesome-LLM-AIOps](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps) (412 ) - A curated list of academic and industrial resources focusing on the application of Large Language Models in Artificial Intelligence for IT Operations (AIOps), covering incident management, log analysis, root cause analysis, and anomaly detection.
- [logpai/awesome-log-analysis](https://github.com/logpai/awesome-log-analysis) (787 ) - A curated repository of research and resources on log analysis, anomaly detection, fault localization, and AIOps, serving as a comprehensive knowledge hub for AI-driven IT operations.
- [logpai/Drain3](https://github.com/logpai/Drain3) (758 Python) - Drain3 is a robust streaming log template miner that extracts and clusters log message templates in real-time using an enhanced Drain algorithm with features like masking, persistence, and memory efficiency.
- [logpai/Log3C](https://github.com/logpai/Log3C) (176 Python) - Log3C is a machine learning-based framework that identifies impactful service system problems by analyzing system logs and correlating them with KPI metrics using cascading clustering and sequence vectorization.
- [logpai/loglizer](https://github.com/logpai/loglizer) (1405 Jupyter Notebook) - Loglizer is a machine learning-based toolkit for automated anomaly detection in system logs, enabling AI-powered IT operations through advanced log analysis.
- [salesforce/logai](https://github.com/salesforce/logai) (781 Python) - LogAI is an open-source library for AI-powered log analytics and anomaly detection, providing a unified platform with advanced machine learning and deep learning models along with an interactive GUI for comprehensive log intelligence.

## Automation & Orchestration

### AI-Powered Automation

- [IBM/cloud-pak-deployer](https://github.com/IBM/cloud-pak-deployer) (154 Jinja) - IBM Cloud Pak Deployer is an automation tool for configuration-based installation and continuous management of OpenShift and IBM Cloud Paks, including Watson AIOps, across various cloud infrastructures.

### Self-Healing Systems

- [keikoproj/active-monitor](https://github.com/keikoproj/active-monitor) (182 Go) - Active-Monitor is a Kubernetes controller that enables deep cluster monitoring and automated self-healing using Argo workflows to ensure reliable and coordinated cluster operations.

## Data & Analytics

### Root Cause Analysis

- [codefuse-ai/codefuse-devops-eval](https://github.com/codefuse-ai/codefuse-devops-eval) (647 Python) - An industrial-first evaluation benchmark and comprehensive suite for assessing large language models in the DevOps and AIOps domain, featuring extensive datasets and leaderboards for model performance tracking.
- [HolmesGPT/holmesgpt](https://github.com/HolmesGPT/holmesgpt) (1903 Python) - HolmesGPT is an AI agent for cloud troubleshooting and alert investigation that integrates with multiple observability and cloud platforms to automate root cause analysis and remediation suggestions, enhancing incident response and operational efficiency.
- [phamquiluan/RCAEval](https://github.com/phamquiluan/RCAEval) (105 Jupyter Notebook) - RCAEval is an open-source benchmark and evaluation framework providing datasets and baseline methods for root cause analysis in microservice systems, supporting metric, trace, and multi-source data for AI-powered DevOps and AIOps applications.

### Anomaly Detection

- [CloudWise-OpenSource/GAIA-DataSet](https://github.com/CloudWise-OpenSource/GAIA-DataSet) (268 ) - GAIA is a comprehensive AIOps dataset designed for analyzing IT operation problems such as anomaly detection, log analysis, and fault localization using real-world-like simulation data and companion anonymized data.
- [jixinpu/aiopstools](https://github.com/jixinpu/aiopstools) (397 Python) - Aiopstools is a Python-based toolkit providing AI-powered modules for anomaly detection, alarm convergence, time series forecasting, and association analysis to enhance IT operations.

### Predictive Maintenance

- [aqstack/sentinel](https://github.com/aqstack/sentinel) (373 Go) - Sentinel is an AI-powered self-healing edge computing agent for Kubernetes that predicts failures, enables autonomous operation during network partitions, and orchestrates workload migrations to enhance edge node reliability and resilience.

## DevOps AI Integration

### Testing Intelligence

- [athina-ai/athina-sdk](https://github.com/athina-ai/athina-sdk) (132 Python) - Athina SDK is a testing and observability platform that helps developers write tests and monitor the performance and reliability of large language model applications in production.

## Cloud & Infrastructure AI

### Infrastructure as Code AI

- [awslabs/aiops-modules](https://github.com/awslabs/aiops-modules) (101 Python) - AIOps Modules is a collection of reusable Infrastructure as Code modules for AI/ML development and operations on AWS, enabling scalable and modular AI-powered infrastructure management using GitOps principles.

## Tools & Utilities

### Visualization & Dashboards

- [evilmartians/agent-prism](https://github.com/evilmartians/agent-prism) (295 TypeScript) - AgentPrism is an open-source React library that visualizes AI agent traces to help debug and understand agent workflows through interactive and hierarchical timelines integrated with OpenTelemetry data.

## Educational Resources

- [OpsPAI/awesome-AIOps](https://github.com/OpsPAI/awesome-AIOps) (302 ) - A curated repository of academic research and industrial resources focused on Artificial Intelligence for IT Operations (AIOps), supporting AI-powered DevOps and infrastructure management.


## License

[<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg">](https://creativecommons.org/publicdomain/zero/1.0/)
