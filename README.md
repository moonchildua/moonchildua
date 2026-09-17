<div align="center">

# 👋 Hi, I'm Dariya

### Senior DevOps / Site Reliability Engineer

AWS · Kubernetes · Terraform · GitOps · Observability

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dariya-mykhaylyshyn-72615739/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/moonchildua)

</div>

> 15 years in IT, 7+ of them in DevOps roles; before that, a system administrator and IT team lead. I build and operate production cloud platforms, with most of my attention on reliability, automation and maintainability. I tend to work in the space between "it runs" and "we can operate this safely at scale".

---


## 💡 What I do

My work is centred on AWS and production Kubernetes: designing infrastructure, moving workloads to repeatable deployment patterns, improving observability and resilience, and replacing manual operations with Infrastructure as Code.

Day-to-day that means:

- Designing and operating AWS infrastructure, including EKS, ECS, EC2, RDS/Aurora, networking and multi-account environments
- Running and evolving production Kubernetes platforms with Helm, ArgoCD, autoscaling, Karpenter etc...
- Writing reusable infrastructure with Terraform and Terragrunt
- Building observability with Prometheus, Grafana, Loki, CloudWatch
- Automating operational work that should not require somebody to do the same thing twice
- Giving developers AI-assisted workflows to create the infrastructure for their services in playground and dev environments without DevOps involvement



## 🛠️ What I've built

Where I'm strongest: planning and building infrastructure, using current tooling, automating repeated work and optimising what already runs. Some examples:

- Designed and built AWS infrastructure from the ground up, separating workloads across multiple environments and codifying the platform with Terraform/Terragrunt so provisioning stays repeatable and maintainable.
- Migrated production workloads from ECS to EKS across AWS accounts, covering the infrastructure, deployment and application sides of the move.
- Reworked asynchronous processing from Redis to SQS, which cut infrastructure cost and operational complexity.
- Built and ran Kubernetes environments on VMware Cloud, alongside FortiGate firewalls, before and between AWS-native setups.
- Designed and deployed infrastructure identity with Teleport for secure access to servers and clusters.
- Built authentication and access patterns around AWS API Gateway, Cognito, Okta and IAM.
- Designed reusable deployment and observability patterns across multiple services and environments.
- Diagnosed false-positive HTTP 503 errors that were skewing SLO dashboards. Separating monitoring artefacts from genuine service failures made the reliability reporting accurate again.
- Extended [Box Anemometer](https://github.com/box/Anemometer) into a centralised slow-query platform with a [custom backend](https://github.com/pdffillerdocker/anemometer-backend) that collects slow queries and automates `EXPLAIN` analysis. At the time it brought MySQL load down from 100% to ~40% and cut RDS costs with it. Newer tools cover this ground now, but the approach paid for itself then.


## ⚙️ Tech

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=aws,kubernetes,docker,terraform,linux,jenkins,githubactions,prometheus,grafana,postgres,mysql,redis,nginx,bash,python,git&perline=8" />
  </a>
</p>

**Cloud & Platform:** AWS (EKS, ECS, EC2, RDS, Lambda, IAM, API Gateway) · Kubernetes · Docker · VMware Cloud · Azure AKS (familiar)  
**Infrastructure as Code:** Terraform · Terragrunt · Helm · Ansible  
**Delivery:** Argo CD · GitHub Actions · Jenkins · TeamCity · GitOps  
**Observability:** Prometheus · Grafana · Loki · CloudWatch · OpenSearch · ELK  
**Data & Messaging:** PostgreSQL · Aurora · MySQL · Redis · DynamoDB · SQS · RabbitMQ  
**Identity & Network:** Teleport · Okta · Cognito · FortiGate · Cisco IOS · Mikrotik  
**Platform:** Karpenter · Istio · Kyverno · AWS Backup  
**Scripting:** Python · Bash

## 💬 Get in touch

Ping me about AWS, production Kubernetes, Terraform, GitOps, observability or database performance. Happy to compare notes with engineers running similar platforms.

---

<div align="center">

Reliable systems, clear ownership and useful automation. Infrastructure should be repeatable, observable and understandable by the engineers who have to operate it at 3 AM.

</div>
