# Cloud Portfolio — AWS & Azure Solutions

A curated portfolio of AWS & Azure solutions covering serverless, Kubernetes, networking, data, security, and CI/CD with IaC.  

Each directory includes a PDF walkthrough and diagrams to show the **why**, **how**, and **trade-offs** behind production-minded designs.

> Goal: demonstrate production-minded designs that balance security, reliability, performance, cost, and operational excellence.

---

## 📌 Table of Contents

- [Portfolio Map (Folders & Artifacts)](#-portfolio-map-folders--artifacts)
- [Suggested Review Roadmap](#-suggested-review-roadmap)
- [Highlighted Project: Three-Tier Serverless Web App](#-highlighted-project-three-tier-serverless-web-app)
- [Core Skills & Projects](#-core-skills--projects)
- [Certifications](#-certifications)
- [How to Use This Repository](#-how-to-use-this-repository)
- [Contact](#-contact)

---

## 🗺️ Portfolio Map (Folders & Artifacts)

> Open a folder, then click the PDF(s) to view the full case study and diagrams.

### ANALYTICS
- [VISUALIZE DATA WITH QUICKSIGHT.pdf](ANALYTICS/VISUALIZE%20DATA%20WITH%20QUICKSIGHT.pdf)  
- [example.pdf](ANALYTICS/example.pdf)

### Account Baselines
- [Set up an Account with AWS.pdf](Account%20Baselines/Set%20up%20an%20Account%20with%20AWS.pdf)

### Compute & Containers
- [Deploy an App Across Multiple Accounts.pdf](Compute%20%26%20Containers/Deploy%20an%20App%20Across%20Multiple%20Accounts.pdf)  
- [Deploy an App with Docker.pdf](Compute%20%26%20Containers/Deploy%20an%20App%20with%20Docker.pdf)

### Data & Databases
- [PART 1 - Visualise a Relational Database.pdf](Data%20%26%20Databases/PART%201%20-%20Visualise%20a%20Relational%20Database.pdf)  
- [PART 2 - Connect a web App to Amazon Aurora.pdf](Data%20%26%20Databases/PART%202%20-%20Connect%20a%20web%20App%20to%20Amazon%20Aurora.pdf)  
- [PART 3 - Connect a web app to Amazon Aurora.pdf](Data%20%26%20Databases/PART%203%20-%20Connect%20a%20web%20app%20to%20Amazon%20Aurora.pdf)  
- [PART 4 - Load Data into a DynamoDB Table.pdf](Data%20%26%20Databases/PART%204%20-%20Load%20Data%20into%20a%20DynamoDB%20Table.pdf)  
- [PART 5 - Query Data with DynamoDB.pdf](Data%20%26%20Databases/PART%205%20-%20Query%20Data%20with%20DynamoDB.pdf)

### DevOps, IaC & CI:CD Pipelines
- [CREATE S3 BUCKETS WITH TERRAFORM.pdf](DevOps,%20IaC%20%26%20CI%3ACD%20Pipelines/CREATE%20S3%20BUCKETS%20WITH%20TERRAFORM.pdf)  
- [PART 1 - Set up a web app using AWS & VS Code.pdf](DevOps,%20IaC%20%26%20CI%3ACD%20Pipelines/PART%201%20-%20Set%20up%20a%20web%20app%20using%20AWS%20%26%20VS%20Code.pdf)  
- [PART 2 - Connect Github Repo with AWS.pdf](DevOps,%20IaC%20%26%20CI%3ACD%20Pipelines/PART%202%20-%20Connect%20Github%20Repo%20with%20AWS.pdf)  
- [PART 3 - Secure Packages with CodeArtifact.pdf](DevOps,%20IaC%20%26%20CI%3ACD%20Pipelines/PART%203%20-%20Secure%20Packages%20with%20CodeArtifact.pdf)  
- [PART 4 - Continuous Integration with CodeBuild.pdf](DevOps,%20IaC%20%26%20CI%3ACD%20Pipelines/PART%204%20-%20Continuous%20Integration%20with%20CodeBuild.pdf)  
- [PART 5 - Deploy a Web App with CodeDeploy.pdf](DevOps,%20IaC%20%26%20CI%3ACD%20Pipelines/PART%205%20-%20Deploy%20a%20Web%20App%20with%20CodeDeploy.pdf)  
- [PART 6 - Infrastructure as Code (IaC) with CloudFormation.pdf](DevOps,%20IaC%20%26%20CI%3ACD%20Pipelines/PART%206%20-%20Infrastructure%20as%20Code%20(IaC)%20with%20CloudFormation.pdf)  
- [PART 7 - Build a CI:CD Pipeline with AWS.pdf](DevOps,%20IaC%20%26%20CI%3ACD%20Pipelines/PART%207%20-%20Build%20a%20CI%3ACD%20Pipeline%20with%20AWS.pdf)

### KUBERNETES
- [PART 1 - Launch a Kubernetes Cluster.pdf](./KUBERNETES/PART%201%20-%20Launch%20a%20Kubernetes%20Cluster.pdf)
- [PART 2 - Set Up Kubernetes Deployment.pdf](./KUBERNETES/PART%202%20-%20Set%20Up%20Kubernetes%20Deployment.pdf)
- [PART 3 - Create Kubernetes Manifests.pdf](./KUBERNETES/PART%203%20-%20Create%20Kubernetes%20Manifests.pdf)
- [PART 4 - Deploy Backend with Kubernetes.pdf](./KUBERNETES/PART%204%20-%20Deploy%20Backend%20with%20Kubernetes.pdf)


### MULTI CLOUD SERIES
- [Multi-Cloud Data Transfer with AWS & GCP.pdf](MULTI%20CLOUD%20SERIES/Multi-Cloud%20Data%20Transfer%20with%20AWS%20%26%20GCP.pdf)

### Networking
- [PART 1 - Build a Virtual Private Cloud (VPC).pdf](Networking/PART%201%20-%20Build%20a%20Virtual%20Private%20Cloud%20(VPC).pdf)  
- [PART 2 - VPC Traffic Flow and Security.pdf](Networking/PART%202%20-%20VPC%20Traffic%20Flow%20and%20Security.pdf)  
- [PART 3 - Creating a Private Subnet.pdf](Networking/PART%203%20-%20Creating%20a%20Private%20Subnet.pdf)  
- [PART 4 - Launching VPC Resources.pdf](Networking/PART%204%20-%20Launching%20VPC%20Resources.pdf)  
- [PART 5 - Testing VPC Connectivity.pdf](Networking/PART%205%20-%20Testing%20VPC%20Connectivity.pdf)  
- [PART 6 - VPC Peering.pdf](Networking/PART%206%20-%20VPC%20Peering.pdf)  
- [PART 7 - VPC Monitoring with Flow Logs.pdf](Networking/PART%207%20-%20VPC%20Monitoring%20with%20Flow%20Logs.pdf)  
- [PART 8 - Access S3 from a VPC.pdf](Networking/PART%208%20-%20Access%20S3%20from%20a%20VPC.pdf)  
- [PART 9 - VPC Endpoints.pdf](Networking/PART%209%20-%20VPC%20Endpoints.pdf)

### STORAGE, Web Hosting & SECURITY
- [Build a Security Monitoring System.pdf](./STORAGE,%20Web%20Hosting%20%26%20SECURITY/Build%20a%20Security%20Monitoring%20System.pdf)
- [Cloud Security with AWS IAM.pdf](./STORAGE,%20Web%20Hosting%20%26%20SECURITY/Cloud%20Security%20with%20AWS%20IAM.pdf)
- [Encrypt Data with AWS KMS.pdf](./STORAGE,%20Web%20Hosting%20%26%20SECURITY/Encrypt%20Data%20with%20AWS%20KMS.pdf)
- [Host a website on Amazon S3.pdf](./STORAGE,%20Web%20Hosting%20%26%20SECURITY/Host%20a%20website%20on%20Amazon%20S3.pdf)
- [Secure Secrets with AWS Secrets Manager.pdf](./STORAGE,%20Web%20Hosting%20%26%20SECURITY/Secure%20Secrets%20with%20AWS%20Secrets%20Manager.pdf)
- [Threat Detection with GuardDuty.pdf](./STORAGE,%20Web%20Hosting%20%26%20SECURITY/Threat%20Detection%20with%20GuardDuty.pdf)

### THREE-TIER SERIES
- [Part 1 – Website Delivery with CloudFront.pdf](THREE-TIER%20SERIES/Part%201%20-%20Website%20Delviery%20with%20CloudFront.pdf)  
- [Part 2 – APIs with Lambda + API Gateway.pdf](THREE-TIER%20SERIES/Part%202%20-%20APIs%20with%20Lambda%20%2B%20API%20Gateway.pdf)  
- [Part 3 – Fetch Data with AWS Lambda.pdf](THREE-TIER%20SERIES/Part%203%20-%20Fetch%20Data%20with%20AWS%20Lambda.pdf)  
- [Part 4 – Build a Three-Tier Web App.pdf](THREE-TIER%20SERIES/Part%204%20-%20Build%20a%20Three-Tier%20Web%20App.pdf)

---

## 🧭 Suggested Review Roadmap

A clear, production-minded sequence:

1) [Account Baselines](./Account%20Baselines/) — set up accounts & guardrails  
3) [STORAGE, Web Hosting & SECURITY](./STORAGE,%20Web%20Hosting%20%26%20SECURITY/) — host static site & secure basics  
4) [THREE-TIER SERIES](./THREE-TIER%20SERIES/) — featured end-to-end app (Parts 1–4)  
5) [DevOps, IaC & CI:CD Pipelines](./DevOps,%20IaC%20%26%20CI%3ACD%20Pipelines/) — build, test, deploy, IaC  
6) [Data & Databases](./Data%20%26%20Databases/) — Aurora & DynamoDB patterns  
7) [Networking](./Networking/) — VPCs, subnets, endpoints, peering  
8) [Compute & Containers](./Compute%20%26%20Containers/) — Docker & multi-account delivery  
9) [KUBERNETES](./KUBERNETES/) — EKS cluster, deploy, scale  
10) [ANALYTICS](./ANALYTICS/) — QuickSight dashboards  
11) [MULTI CLOUD SERIES](./MULTI%20CLOUD%20SERIES/) — AWS ↔ GCP data flows

---

## ⭐ Highlighted Project: Three-Tier Serverless Web App

- **Architecture:** S3 + CloudFront → API Gateway → Lambda → DynamoDB  
- **Focus:** CORS (API Gateway & Lambda), least-privilege IAM, CloudFront cache strategy, `userId` as partition key for O(1) lookups.  
- **Where to look:** see the four PDFs under **THREE-TIER SERIES** above.

---

## 🧠 Core Skills & Projects

**Kubernetes (K8s):** EKS, cluster provisioning, deployments/rollouts, HPA, RBAC, Ingress/ALB, ConfigMaps/Secrets, Helm

**IaC (Infrastructure as Code):** Terraform, CloudFormation, modular stacks, environment parity, CI/CD-driven provisioning

**AWS:** S3, CloudFront, Lambda, API Gateway, DynamoDB, Aurora, EKS, VPC, IAM, KMS, Secrets Manager, CloudWatch, CodePipeline/CodeBuild/CodeDeploy

**DevOps & CI/CD:** Git/GitHub, build/test/package promotions, artifact security (CodeArtifact), blue/green & rolling deploys

**Containers:** Docker images, multi-stage builds, registries, runtime hardening

**Data & Analytics:** Amazon Aurora (RDS), DynamoDB (keys/GSIs/TTL/RCU/WCU), QuickSight

**Security:** IAM least-privilege, private networking, VPC endpoints, encryption at rest/in transit, secrets management, audit & logging


---

## 🥇 Certifications

- **AWS Certified Solutions Architect – Professional**  
- **Microsoft AZ-305 (Azure Solutions Architect)**  
- **Scrum Master • Product Owner • Agile Coach** (Scrum Institute)

---

## 📖 How to Use This Repository

- **Browse by topic:** open any folder above; read the PDF(s) in order.  
- **Reproduce selectively:** most projects include prerequisites and step-by-steps; clone, adapt, and run in a sandbox AWS account.  
- **Connect the dots:** follow the **Suggested Review Roadmap** for a quick, cohesive tour.

> Tip: If a link with spaces/symbols doesn’t open directly, click into the folder and select the PDF from there.

---

## 📬 Contact

- **Email:** abiuwakehinde96@outlook.com  
- Open to **Solutions Architect** roles (remote/hybrid).  
- Open an **Issue** here to request a live walkthrough.
