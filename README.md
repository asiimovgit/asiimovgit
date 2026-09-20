# Jithin Jacob

**Senior DevOps Engineer · Site Reliability Engineer · Platform Engineering**

Kerala, India · [LinkedIn](https://linkedin.com/in/jithinjacob24x7)

Nearly 8 years building secure, highly available AWS and Kubernetes platforms. Most of my
work lives in private infrastructure repositories, so this profile is mainly a summary of
what I do rather than a portfolio. I'm slowly extracting the genuinely reusable pieces into
public repos.

---

## What I work on

**GitOps control planes.** Multi-tenant GitOps platform running 34 OpenTofu stacks through
FluxCD, Kustomize and tf-controller. Wrote a cgroup-aware Python webhook router with an
in-memory Kubernetes API cache, an 8-worker thread pool and burst coalescing that folds
500-commit bursts into single reconciles — cut API server load by 90% and eliminated kernel
CFS throttling and webhook timeouts.

**Kubernetes platform engineering.** IPv6-primary dual-stack Amazon EKS running 10
microservices across dev, staging and production, with Istio service mesh, HPA, Pod
Disruption Budgets, Gateway API and Karpenter node autoscaling. Ingress isolated onto a
dedicated nodepool. 99.99% uptime, 40% lower provisioning latency.

**Internal developer platforms.** A self-service CLI (Python, GNU Make, Helm) that
auto-scaffolds microservice infrastructure, SOPS secret templates and EKS Pod Identity
roles — developer onboarding went from 2 hours to under 2 minutes. Restructured global
environments into 6 modular Terraform stacks on independent S3 backends, cutting plan time
75% and removing state-lock contention.

**FinOps.** Automated scheduler that scales non-production namespaces to zero on weekday
evenings and through weekends, letting Karpenter consolidate idle nodes, with EventBridge
and Lambda stopping Aurora clusters and pausing MongoDB Atlas. Non-production runtime
dropped from 168 to 50 hours a week — a 70% reduction.

**Cloud governance and networking.** Multi-account AWS governance with Control Tower,
Organizations and IAM Identity Center across 15+ production projects: RBAC permission sets,
short-lived STS credentials, automated SCP guardrails. Cross-account hub-and-spoke network
over Transit Gateway, Route 53 Resolvers and PrivateLink with fully private DNS resolution,
plus an event-driven dual-ISP VPN failover engine using atomic SSM locking that fails over
in under 30 seconds.

**Observability and SRE.** Multi-tenant observability on OpenTelemetry Collector,
VictoriaMetrics, Datadog and Grafana — metrics storage down 60%, MTTR down 45%, telemetry
billing down 35%. PagerDuty alert grouping and escalation policies that cut on-call noise
50% and brought MTTA under a minute.

---

## Tech

**Cloud & IaC** — AWS (EKS, ECS, Fargate, Lambda, Transit Gateway, Control Tower,
Organizations, IAM Identity Center), Terraform, OpenTofu, Ansible

**Kubernetes** — EKS, Helm, Kustomize, FluxCD, Istio, Gateway API, Karpenter, HPA, PDB

**Data & AI** — Snowflake, Amazon Bedrock, Amazon Neptune, Apache Airflow, PySpark, AWS
Glue, DynamoDB, ClickHouse, SolrCloud

**CI/CD & Automation** — GitLab CI, Jenkins, AWS CodePipeline, CodeBuild, SonarQube,
Python, Bash

**Observability** — Datadog, New Relic, Prometheus, Grafana, OpenTelemetry,
VictoriaMetrics, CloudWatch, PagerDuty

**Security** — Zero-trust architecture, least-privilege IAM, EKS Pod Identity, IRSA,
Mozilla SOPS, AWS KMS, Secrets Manager, Secrets Store CSI Driver

**Linux** — RHEL, CentOS, Ubuntu; server hardening, TCP/IP, DNS, VPN/IPSec

---

## Certifications

- AWS Certified DevOps Engineer – Professional (DOP-C02)
- AWS Certified Solutions Architect – Associate (SAA-C03)
- Red Hat Certified Engineer (RHCE)
- Red Hat Certified System Administrator (RHCSA)
