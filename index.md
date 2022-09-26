---
layout: default
title: CV
---

## Keyword Optimized Skill Set

### General 

| Topic | App/Tool | 
|:-------------:|:--------:|
| Operating Systems      | RedHat, CentOS, Amazon Linux, Debian, Ubuntu, Mint, Alpine, MacOS          |
| IaC, Config Management | Terraform, Serverless, Puppet, Ansible                                     |
| CI / CD                | CircleCI, Jenkins, Bitbucket Pipelines, GitHub Actions, DroneCI, Gitlab CI |
| Containerization       | Docker, Podman, Kaniko, K8s v1.11-1.23                                     |
| Kubernetes Apps/Tools  | Helm, Helmfile, Kustomize, Prometheus/Grafana, Nginx Ingress Controller, Lets Encrypt/cert-manager, K8up, KIND, K3s, Lens, k9s, ArgoCD |
| Databases              | MySQL/MariaDB, PostgreSQL, SQLite, DynamoDB, Mongo, Cassandra              |
| computer_languages     | Python (Flask/Django), JavaScript (Node), BASH, Go, C# (Unity 2020)        |
| Human Languages        | English (native speaker), Dutch (A1-A2)                                    |

### AWS

| Category | Amazon Web Service | 
|:---------:|:------------------:|
| RBAC/Firewall  | IAM, Security Groups, NACL (VPC)            |
| InfoSec        | GuardDuty, CloudTrail, Inspector, KMS, ACM  |
| Networking     | VPC, Route53, API GateWay, ELB              |
| Compute        | EC2, Lambda, SNS, SSM, EKS, ECS, Fargate    |
| Monitoring     | CloudWatch, OpenSearch, Kibana              |
| Storage        | RDS, S3, ECR, EFS, EBS                      |

---

# Experience


## Freelance Platform Engineer @ Abcam
### Amsterdam, Netherlands - remote (May 2022 - June 2022)
- Helped with tech debt Devops tasks, including ArgoCD, setting up Kafka on k8s, Prometheus metrics and alerting, and Gitlab CI pipelines optimization and troubleshooting, and docker/k8s training.



## Lead DevOps Engineer                   ReaQta, An IBM Company
## Amsterdam, Netherlands - remote                     (December 2021 - April 2022)
- Helping integrate ReaQta’s AWS infra into IBM while helping to train an additional team mate, and move forward the hiring of additional team members/determine future ways of working
- Helped design and implement ansible deployment/upgrade pipelines with GitLab Runners for remote customer deployments both bare metal and AWS EC2 instances.
- Imported core bespoke customer infra from AWS into terraform in revision control.
- Updated product InfoSec standards, especially around logging from EC2 instances, docker, and VPC flow logs and long term log storage solutions using Glacier, and deployed various tooling for monitoring and alerting of their docker/EC2 infrastructure via AWS cloudwatch and datadog’s Vector
- Benchmarked (for wall/CPU time + mem per millions of requests) and deployed Nginx WAF (web app firewall) with OWASP CRS (core rule set) docker image across multiple sites in Singapore and the EU


## Senior DevOps Engineer                          Paladin Studios
## Den Haag, Netherlands - remote                (July 2021 - December 2021)
- Upgraded CI/CD workflows; laid out framework for migrating from locally hosted Jenkins to GitHub Actions hybrid self hosted runners/GHA runners
- Solved Unity (2019-2020.3) broken build automation job errors, requiring deep dives into C# game code, as well as set up new build automation jobs for new games
- Reduced automated Unity Android/iOS build target times by about 30% with multiple dockerized setups of Unity Accelerator
- Diagnosed infosec hygiene issues, and created a roadmap for future policies, alongside a comprehensive DevOps roadmap to be completely cloud native by 2022
- Created DEI (Diversity, Equity, Inclusion) training on LGBTQIA+ Allyship


## Cloud Platform Engineer                            DAZN
## Amsterdam, Netherlands - remote                     (Dec 2020 - June 2021)
- Worked to help the cloud platform team standardize their user management in Azure, GCP, and AWS environments for DAZN’s product engineering department
- Designed/implemented architecture, written in Go, for hourly automated AWS IAM credential refreshes to assist in moving to GitHub Actions from Drone CI, via AWS Lambdas and DynamoDB
- Managed deployments and helped coordinate engineering teams to troubleshoot issues, especially with internal tooling and Hashicorp Vault

## Senior DevOps Engineer                     VIZIO (Contract via Globant)
## Seattle, WA, USA - remote                      (August 2019 - August 2020)
- Designed and built out IaC (Terraform/Serverless) for monitoring VIZIO’s AWS infrastructure, including ECS, RDS, Redis, ELB, and Lambda via Cloudwatch. Set up PagerDuty as well as had Cloudwatch send alerting via SNS to PagerDuty, which also alerted Slack/emailed core stakeholders when anomalies were detected in a service’s baseline expected thresholds. Also, Generated Datadog/Cloudwatch dashboards
- Revamped VIZIO’s CI/CD process for deploying firmware/asset bundles to TVs. Switched them from three 24/7 running EC2 instances, to a Dockerized Python3 environment that spun up via CircleCI to process build configs, and generate appropriate software bundles for specific models of TVs


## Senior DevOps Engineer                        ReachNow / ShareNow / BMW
## Seattle, WA, USA                            (August 2018 - July 2019)
- Developed a new pipeline and project creation script for the app and website using Python, Jenkins, and Kubernetes on AWS EC2 instances (With kops). Moved everything from ECS/docker on EC2 to Kubernetes.
- Other CI/CD related tech: bitbucket, codeship, AWS ECS/Fargate
- Responsible for upgrades to infrastructure such as PostgreSQL, MongoDB, and adjustments to ECS/Fargate
- Responsible for responding to technical alerts for my services and an on call rotation for general outages


## DevOps Engineer                            Analog Devices (Contract)
### Seattle, WA, USA - Remote                        (March 2018 - Aug 2018)
- Full stack dev work for ADI project management webapp using Perl on the backend
- Configured and wrote integrations between Perforce and Atlassian in Perl/Python (P4DTG, Jira/Confluence/Swarm REST APIs). Also did PoC for Fisheye/Crucible
- Wrote python handling app to process files ClamAV deemed suspicious


## Senior Software Engineer                    MinOps Inc. (Contract)
### CA, USA - Remote                             (July 2017 - March 2018)
- Primary engineer on product to index AWS infrastructure and make it queryable via SQL 
- Feature/bug work to the primary product, which required working with Lambda, EC2, SNS, Route53, CloudWatch, CloudFront, CloudFormation, S3, IAM
- Responsible for website (wrote front/backend,  development pipeline)

Software Engineer                            Cloudian
San Mateo, CA, USA                             (April 2016 - July 2017)
- Maintained existing code, in both BASH and Python for the Hyperstore installer (Object storage/searching, in your local datacenter with an AWS S3 like API for hybrid clouds)
- Tasked with leading project to rewrite roughly 20,000 lines of BASH into Python, while also mentoring a junior SWE in Python
Provided Linux and web expertise, e.g. snapshots, DNS, SSL, and InfoSec matters


## DevOps Engineer                           Analog Devices Inc.
## San Jose, CA, USA                            (Nov 2013 - April 2016)
- Wrote automation scripts/webapps to cut down on direct admin to user interactions. Designed/Wrote AutoVM in Python: supported creation/management of VMs via a web app, RESTful API, or CLI. Capable of mass rebuilds. Utilized VMware vSphere (Pyvmomi)
- Supported internal research and development for RHEL/Solaris infrastructure, and managed a number of services, including Puppet, Nagios, LDAP, Perforce, HAProxy, and bare metal hardware for several large compute farms


## InfoSec Analyst                                    Apple (contract)
## Sunnyvale, CA, USA                                  (Aug 2013 - Nov 2013)
- Created list of suspicious users, and tracked them across 17.0.0.0/8, especially during important product launches, and analyzed payloads of any packets deemed suspicious 
- Helped create use cases for alerting using various logging sources including netflow anomalies via Lancope StealthWatch and Arbor’s NSI/TMS


Site Reliability Operations Analyst                      Apigee (contract)
Palo Alto, CA, USA                             (June 2013 - July 2013)
- Identified issues that arose with scale in Apigee’s LAMP stacks on AWS
Managed and supported networking, Route53 DNS, apache configs, ELBs, memory leaks, and provided consultation on automation of dev hassles


## Unix/Linux Support Engineer                    Centrify Corp.
## Sunnyvale, CA, USA                                  (Oct 2012 - May 2013)
- Troubleshot Centrify products dealing with Kerberos across AD/LDAP and role based management, including ACLs. Also, Did deep dives into SSH, PAM/LAM stacks across multiple distros of Unix/Linux


## Linux Sysadmin                                    Nexcess.net LLC
### Dearborn, MI, USA                                  (Jan 2012 - Oct 2012)
- LAMP stack admin work with a heavy focus on the web and customer facing systems for web hosting clients. Supported PHP based websites, especially CMS like Wordpress and Magento. Resolved SSL issues, and managed DNS for clients.
