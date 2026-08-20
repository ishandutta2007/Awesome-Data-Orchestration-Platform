# Awesome-Data-Orchestration-Platform

## Top Data Orchestration Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Workflow Orchestration, Data Pipelines, Durable Execution, Asset-Based Scheduling, Event-Driven Automation & ML/AI Workflows*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Orchestration**. These tools schedule, monitor, and manage complex workflows and data pipelines, handling dependencies, retries, observability, and scaling across batch, streaming, and long-running processes.



**Examples** include Astronomer, Prefect Cloud, Dagster Cloud, Kestra, Control-M Cloud, Windmill, Orkes Conductor, Apache Airflow MWAA, Flyte Cloud, and Temporal Cloud (the category leaders).



**Open-source emphasis**: This section is heavily expanded. Nearly every major commercial offering is built on a strong open-source core (Airflow, Prefect, Dagster, Kestra, Temporal, Flyte, Windmill, Conductor), making self-hosted production orchestration widely accessible.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Astronomer (Astro)](https://www.astronomer.io/)**  

  Managed Apache Airflow platform with enterprise governance, multi-cloud deployment, observability, and operational tooling on top of the Airflow core.



- **[Prefect Cloud](https://www.prefect.io/)**  

  Managed service for the Prefect workflow orchestration framework, offering hybrid execution, observability, and Python-native dynamic workflows.



- **[Dagster Cloud / Dagster+](https://dagster.io/)**  

  Managed offering of the Dagster asset-oriented orchestrator, focused on software-defined assets, lineage, and modern data platform development.



- **[Kestra](https://kestra.io/)**  

  Declarative, YAML-based orchestration platform (open-source core + cloud) supporting scheduled and event-driven workflows with extensive plugins.



- **[Control-M Cloud (BMC)](https://www.bmc.com/)**  

  Enterprise workload automation and orchestration platform for complex, mission-critical job scheduling across hybrid environments.



- **[Windmill](https://www.windmill.dev/)**  

  Open-source and cloud workflow engine that turns scripts into production workflows and internal tools with auto-generated UIs.



- **[Orkes Conductor](https://orkes.io/)**  

  Managed service built on Netflix Conductor for durable, scalable microservice and workflow orchestration.



- **[Amazon MWAA (Managed Workflows for Apache Airflow)](https://aws.amazon.com/mwaa/)**  

  Fully managed Apache Airflow service on AWS for running data pipelines without managing the underlying infrastructure.



- **[Flyte Cloud](https://flyte.org/)**  

  Managed offering of the Flyte Kubernetes-native workflow orchestrator, strong for ML and data pipelines with typed interfaces.



- **[Temporal Cloud](https://temporal.io/)**  

  Managed service of the Temporal durable execution platform, ideal for long-running, fault-tolerant workflows and microservices.



## Open-Source GitHub Projects

- **[Apache Airflow](https://github.com/apache/airflow)**  

  The most widely adopted open-source workflow orchestrator, using Python DAGs to define, schedule, and monitor complex data pipelines.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Modern, Python-native open-source workflow orchestration framework focused on dynamic workflows, retries, and developer experience.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open-source data orchestrator built around software-defined assets, strong lineage, testing, and observability for data platforms.



- **[Kestra](https://github.com/kestra-io/kestra)**  

  Open-source, declarative YAML-based orchestration engine supporting event-driven and scheduled workflows with a large plugin ecosystem.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Leading open-source durable execution platform for long-running, reliable workflows with multi-language SDKs.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open-source Kubernetes-native workflow orchestrator designed for data and ML pipelines with strong typing and reproducibility.



- **[Windmill](https://github.com/windmill-labs/windmill)**  

  Open-source workflow engine and internal-tool platform that turns scripts (Python, TypeScript, Go, Bash, etc.) into production workflows.



- **[Netflix Conductor / Orkes](https://github.com/Netflix/conductor)**  

  Open-source microservice orchestration engine originally from Netflix, powering durable and scalable workflow execution.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open-source Kubernetes-native workflow engine for container-native CI/CD and data/ML pipelines.



- **[Mage / other modern orchestrators](https://github.com/)**  

  Notebook-friendly and low-code open-source pipeline tools that complement or alternative traditional DAG-based systems.



### Additional Strong Open-Source Options

- Luigi (historical but still used for simpler pipelines).

- Kedro for software-engineering practices in data pipelines.

- n8n and Activepieces for lower-code / automation-style orchestration.

- Kubeflow Pipelines for ML-specific Kubernetes workflows.

- Custom orchestrators built on Kubernetes Jobs, Celery, or message queues.

- Event-driven frameworks that integrate with the tools above.



**Frameworks for building custom systems**: For classic data pipelines choose **Apache Airflow** or **Dagster**; for dynamic Python workflows use **Prefect**; for durable long-running processes use **Temporal**; for Kubernetes-native ML use **Flyte**; for declarative multi-language automation use **Kestra** or **Windmill**. Self-host any of these, add observability (OpenTelemetry, Prometheus), and integrate with your existing data stack. Managed cloud versions exist for teams that prefer not to operate the control plane.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Orchestration systems are critical infrastructure. Open-source solutions are production-proven at massive scale but still require careful configuration of scaling, secrets management, monitoring, and high availability.

- Always design workflows to be idempotent and observable, and plan for failure recovery regardless of the platform chosen.



---

**Made for data engineers, platform teams, and ML engineers building reliable automated workflows.**

Let's make data and process orchestration more open, observable, and resilient.
