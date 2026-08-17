<div align="center">

# Ahmad Wasim

**DevOps & Cloud Infrastructure Engineer**

Multan & Lahore, Pakistan &nbsp;·&nbsp; Associate DevOps Engineer @ GoCloud &nbsp;·&nbsp; B.S. Computer Science (CGPA: 3.80)

[![AWS Certified](https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://linkedin.com/in/ahmedwsiim)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ahmedwsiim-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmedwsiim)
[![Portfolio](https://img.shields.io/badge/Portfolio-ahmedwsiim.github.io-10B981?style=for-the-badge&logo=google-chrome&logoColor=white)](https://ahmedwsiim.github.io)
[![Twitter](https://img.shields.io/badge/X-@ahmedwsiim-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/ahmedwsiim)

</div>

<br>

## Profile

DevOps and Cloud Infrastructure Engineer specializing in enterprise-grade AWS infrastructure, Infrastructure as Code (Terraform), zero-trust security automation, and FinOps. Currently engineering automated multi-region architectures, serverless compliance pipelines, and containerized microservices at GoCloud. 

**Core Competencies:** Multi-Region Cloud Architecture · Infrastructure as Code (Terraform) · CI/CD Automation (OIDC) · DevSecOps & Log Governance · FinOps & Cost Optimization · Container Orchestration (ECS / EKS)

<br>

## Work Experience

**Associate DevOps Engineer** — GoCloud
<br><sub>Jun 2026 – Present &nbsp;·&nbsp; On-site</sub>

- **Multi-Tenant FinTech Architecture:** Designed an end-to-end multi-tenant infrastructure on AWS using Terraform and serverless patterns. Enforced account isolation via AWS Control Tower, data isolation via PostgreSQL Row-Level Security (RLS), and automated ingestion/PII redaction via Step Functions and Amazon Comprehend. Replaced multi-hour manual rollouts with a 15-minute 1-click CI/CD workflow.
- **Automated Security & Log Governance:** Engineered a serverless Python 3.12 Lambda engine aggregating findings across AWS Security Hub, GuardDuty, Inspector V2, Config, and WAF into daily automated reports. Hardened audit lifecycles across 40+ CloudWatch log groups, VPC Flow Logs, and CloudTrail, saving 550–730 analyst hours annually.
- **FinOps & Cost Optimization:** Re-architected log ingestion pipelines (CloudFront Access Logs vs. standalone WAF logging), slashing logging spend by ~90% ($500–$1,500 annual savings) and eliminating indefinite retention costs.
- **Container & Cluster Operations:** Built and deployed microservices on AWS ECS Fargate and EKS with automated TLS, ALB ingress, and auto-scaling policies.
- **Zero-Trust CI/CD:** Automated GitHub Actions delivery pipelines using OIDC authentication and AWS Systems Manager (SSM), eliminating long-lived credentials and public SSH exposure across client environments.

<br>

**DevOps Engineer** — HashTurn
<br><sub>Oct 2025 – May 2026 &nbsp;·&nbsp; On-site</sub>

- **Full-Stack & Cloud Deployments:** Architected and deployed scalable production applications (MERN, PERN, Python Flask) across AWS and Linux VPS environments with NGINX reverse proxying and automated SSL/TLS management.
- **System Architecture:** Spearheaded foundational architectural decisions and automated development environments, serving as a technical proxy for the engineering team.
- **Desktop System Delivery:** Architected and launched *HashDash*, an HR and workforce management desktop application using Electron.js, Vite, and WebRTC.
- **Automated Data Scraping:** Developed high-throughput automated scrapers to optimize internal workflows and multi-source data aggregation.

<br>

**DevOps Intern** — Systems Limited
<br><sub>Jul 2025 – Sep 2025 &nbsp;·&nbsp; On-site</sub>

- **CDN Acceleration:** Codified CI/CD pipelines for immutable artifact publishing to AWS S3 and CloudFront cache invalidation, reducing global asset delivery latency by 50%.
- **Cloud Modernization:** Containerized full-stack applications with Docker, configured NGINX reverse proxies with SSL termination, and provisioned multi-cloud infrastructure (AWS EC2, Azure VMs) via Terraform.
- **Least-Privilege IAM:** Enforced strict IAM role policies, secure secret management, and deterministic artifact versioning.

<br>

**Networking & Infrastructure Intern** — Faysal Bank Limited
<br><sub>Jul 2024 – Aug 2024 &nbsp;·&nbsp; On-site</sub>

- Configured enterprise routing, switching, and patch infrastructure across LAN/WAN networks.
- Resolved 150+ IT infrastructure tickets (95% first-call resolution rate) and assisted with Oracle Financials SQL reporting workflows.

<br>

## Technical Skills

| Domain | Technologies & Tools |
|---|---|
| **Cloud Providers** | Amazon Web Services (AWS), Microsoft Azure, Google Cloud Platform (GCP) |
| **AWS Core Services** | EC2, ECS Fargate, EKS, Lambda, S3, CloudFront (OAC), RDS Aurora Serverless v2, ElastiCache Redis, Route 53, Control Tower, Step Functions, PrivateLink, KMS |
| **Infrastructure as Code** | Terraform, AWS CloudFormation |
| **Containers & Orchestration** | Docker, Docker Compose, Kubernetes (EKS), Container Registries (ECR, Docker Hub) |
| **CI/CD & Automation** | GitHub Actions (OIDC Federation), Bash Scripting, Python Scripting |
| **Security & Observability** | AWS Security Hub, GuardDuty, Inspector V2, AWS Config, WAF v2, CloudTrail, CloudWatch (Metric Alarms & ML Anomaly Detection), IAM (Least-Privilege, RLS) |
| **Web & Networking** | NGINX, Apache2, REST APIs, WebRTC, DNS Management, Let's Encrypt SSL/TLS, VPC Peering & Endpoints |
| **Languages & Frameworks** | Python, JavaScript/TypeScript, Node.js, PHP, Flask, Django, React, Next.js |
| **Databases** | PostgreSQL, MySQL, MongoDB, Redis |

<br>

## Featured Cloud & DevOps Projects

### Multi-Region AWS Production Infrastructure & Automated DR
- Provisioned a fault-tolerant multi-region SaaS platform using modular **Terraform**.
- **Compute & Ingress:** 3-AZ VPC topology in `us-east-1` with ECS Fargate auto-scaling (1–10 tasks), Application Load Balancers, and CloudFront CDN with Origin Access Control (OAC).
- **Data & State Layer:** Aurora PostgreSQL 17.7 Global Database (Serverless v2) with block-level replication to `us-west-2` DR cluster (**RTO < 60s, RPO < 1s**), alongside Multi-AZ ElastiCache Redis.
- **Security & Observability:** Hardened edge with AWS WAF v2 rate-limiting, regional CMK encryption in KMS, CloudWatch operational dashboards, and Machine Learning Anomaly Detection bands.

### Automated Enterprise Patch Management Pipeline
- Designed an automated EC2 patching engine using **Terraform**, **AWS PrivateLink**, and **AWS Systems Manager (SSM)**, removing all public internet access during maintenance cycles.
- Integrated an event-driven compliance engine via **AWS Lambda** and **EventBridge** that automatically discovers instances via IAM tags and renders real-time patch status dashboards in CloudWatch.

### Resilient Content Aggregator
- Architected and deployed a multi-protocol data ingestion pipeline utilizing Playwright, Telethon, and translation APIs.
- Containerized using **Docker Compose** and secured with NGINX reverse proxy, automated SSL/TLS renewals, and Cloudflare WAF protection.
- Live: [burma-news.org](https://burma-news.org/)

### HashDash Management System
- Cross-platform desktop management and monitoring application built with **Electron.js**, **Vite**, and **WebRTC** for real-time employee communication and operational oversight.

<br>

## Certifications & Education

**Certifications:**
- **AWS Certified Solutions Architect – Associate (SAA-C03)** — Amazon Web Services (2026–2029)
- **AWS Partner: Migration Foundations Knowledge** — Amazon Web Services (2026)
- **Oracle Cloud Infrastructure Certified** — Oracle (2024)
- **Containers, Docker, Kubernetes & OpenShift** — IBM
- **Strategies for Cloud Security Risk Management** — Google Cloud
- **Cybersecurity & Infrastructure Security** — U.S. Department of Homeland Security

**Education & Leadership:**
- **B.S. in Computer Science** — Bahauddin Zakariya University (2022 – 2026) &nbsp;·&nbsp; **CGPA: 3.80**
- **DevOps Lead** — Microsoft Learn Student Ambassadors (MLSA-Multan, 2024 – 2025)
- **Core Team Member** — Google Developer Student Clubs (GDSC-BZU, 2024 – 2025)
- **Initiator & Organizer** — *Code&Clash* Tech Competition

<br>

## GitHub Activity

<div align="center">

<a href="https://github.com/ahmedwsiim">
  <img src="https://img.shields.io/github/followers/ahmedwsiim?style=for-the-badge&logo=github&color=8ab4f8&labelColor=0d1117&label=Followers" alt="GitHub Followers" />
</a>
&nbsp;
<a href="https://github.com/ahmedwsiim?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-View%20All-8ab4f8?style=for-the-badge&logo=github&labelColor=0d1117" alt="View Repositories" />
</a>

<br><br>

<sub>Live contribution history, streaks, and pinned repositories are available on my <a href="https://github.com/ahmedwsiim">GitHub profile</a>.</sub>

</div>

<br>

<div align="center">

<sub>Ahmad Wasim &nbsp;·&nbsp; <a href="https://linkedin.com/in/ahmedwsiim">LinkedIn</a> &nbsp;·&nbsp; <a href="https://x.com/ahmedwsiim">Twitter</a> &nbsp;·&nbsp; <a href="https://ahmedwsiim.github.io">Portfolio</a></sub>

</div>
