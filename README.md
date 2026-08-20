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

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Astronomer (Astro)](https://www.astronomer.io/)** | Managed Apache Airflow platform with enterprise governance, multi-cloud deployment, observability, and operational tooling. | Starts at **$0.35/hour** (~$250/month) base for Developer tier deployments + compute resource consumption. | **14-day free trial** with **$20 in platform/compute credits** (no credit card required upfront). No permanent free tier. |
| **[Prefect Cloud](https://www.prefect.io/)** | Managed workflow orchestration platform offering hybrid execution, observability, and Python-native dynamic workflows. | **Starter Plan**: **$100/month** (up to 3 users, 20 deployments, 75 hrs serverless compute); **Team Plan**: **$100/user/month**. | **Hobby Plan (Free Forever)**: 2 users, 5 deployments, 500 minutes of serverless compute/month, 7-day run history, and 625 API req/min. |
| **[Dagster+ / Dagster Cloud](https://dagster.io/)** | Managed data orchestrator focused on software-defined assets, lineage, and modern platform development. | **Solo Plan**: **$10/month** base fee + $0.04/credit + $0.010/min serverless compute; **Starter Plan**: **$100/month** base fee + $0.035/credit. | **30-day free trial** with full feature access and included trial execution credits. No permanent free tier. |
| **[Kestra Cloud](https://kestra.io/)** | Declarative, YAML-based orchestration platform supporting scheduled and event-driven workflows with 600+ plugins. | Free self-hosted OSS; Managed Cloud/Enterprise tiers require custom sales quote (~**$5–$10/month** on 1-click cloud templates like Railway). | **14 to 30-day trial** available upon demo request; permanent free open-source edition (Apache 2.0) with unlimited workflow executions. |
| **[Control-M Cloud (BMC Helix)](https://www.bmc.com/)** | Enterprise workload automation and orchestration platform for complex, mission-critical job scheduling across hybrid environments. | **Starter Pack**: Starts at **$2,400/month** (billed annually) for full SaaS orchestration, SLA management, and 24x7 support. | **30-day free trial (POC)** with full functionality and pre-configured test workflow environments. No permanent free tier. |
| **[Windmill](https://www.windmill.dev/)** | Open-source and cloud workflow engine and UI builder that turns scripts (Python, TypeScript, Go, Bash, SQL) into production workflows. | **Team Plan**: Starts at **$20/developer seat/month** ($10/operator seat/month) + compute usage ($0.001/execution overage). | **Community Plan (Free Forever)**: Includes up to 3 workspaces and 1,000 cloud executions/month (or unlimited executions if self-hosted OSS). |
| **[Orkes Conductor](https://orkes.io/)** | Managed orchestration service built on Netflix Conductor for durable, high-throughput microservice and AI workflow execution. | Enterprise Cloud plans are quote-based via custom contract / AWS Marketplace SaaS listing; Developer Edition is completely free. | **Developer Edition (Free Forever)**: Free hosted sandbox at `developer.orkescloud.com` with no expiration and full Conductor OSS + AI tooling; **14-day trial** for Orkes Cloud. |
| **[Amazon MWAA](https://aws.amazon.com/mwaa/)** | Fully managed Apache Airflow service on AWS for running data pipelines without managing underlying infrastructure. | Starts at **$0.49/hour** (~$353/month for US East) for Small environment + $0.055/hour per additional worker/scheduler + $0.10/GB-month metadata storage. | **No AWS Free Tier** (billed from first hour of creation). Free local development testing available via open-source `aws-mwaa-local-runner`. |
| **[Flyte Cloud / Union.ai](https://flyte.org/)** | Managed Kubernetes-native workflow orchestrator tailored for data, ML, and AI pipelines with strong typing. | **Union Serverless**: Pay-as-you-go starting at **$0.12/CPU Core-hour**, **$0.029/GB-hour memory**, and **$0.71/GPU-hour** (T4); Managed Union Cloud from ~$2,500/month. | **Free trial** with **$30 in serverless compute credits** (GitHub login, no credit card required). No permanent free tier. |
| **[Temporal Cloud](https://temporal.io/)** | Managed service of the Temporal durable execution platform for resilient, long-running workflows and microservices. | **Essentials Plan**: Starts at **$100/month** base (includes 1M Actions, 1 GB Active Storage, 40 GB Retained Storage; $50/M Actions thereafter); **Business**: Starts at **$500/month**. | **Free trial** with **$1,000 in evaluation credits** for new accounts (up to $6,000 credits for eligible startups). No permanent free tier. |



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
