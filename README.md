<div align="center">

![Suheb Ali Banner](https://raw.githubusercontent.com/ersuheb/ersuheb/main/banner.svg)

### Cloud Platform Lead @ E2E Networks
**I keep production infrastructure running, and I fix it when it doesn't.**

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ersuheb@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ersuheb/)

</div>

<br/>

## What I Work On

I lead the Cloud Platform team responsible for the reliability of a large-scale production fleet (80+ servers) spanning customer-facing load balancers, databases, message queues, and a GPU/Kubernetes platform.

**Production operations & incident response**
- Live incident response on production systems: stuck kernel-level processes, duplicate-IP network conflicts, hardware failures, OOM/resource exhaustion
- Root-cause investigation that goes all the way down: from an application symptom, through the load balancer, through the network path, to the actual kernel/hardware layer when needed
- Zero-downtime changes on live production traffic: binary upgrades, TLS migrations, config rollouts, all verified empirically (PID continuity, connection counts, real traffic health) before being called done

**Platform & infrastructure engineering**
- Kubernetes platform operations: workload scheduling, GPU node pools, networking (CNI/Cilium), cluster-internal PKI
- TLS migrations on production messaging infrastructure (RabbitMQ) across multiple data centers, with zero dropped connections
- Load balancer architecture and hardening (HAProxy/Nginx): TLS termination, zero-downtime upgrades, backend health monitoring

**Security & compliance**
- Led vulnerability remediation across an 80+ server fleet end-to-end: CVE patching, TLS/cipher hardening, certificate lifecycle, access control
- Built monitoring and alerting for gaps that generic tooling misses: stale certificates, silent backend failures, service drift

**Monitoring & observability**
- Designed and built custom Zabbix checks, triggers, and alert routing where off-the-shelf monitoring fell short
- A consistent principle: if something breaks and nothing alerts on it, that's a bug in the monitoring, not just the incident

**Currently**
- Standing up the SRE function for Blaze, E2E's GPU inference platform (Kubernetes, vLLM/SGLang serving, multi-model routing)

<br/>

## How I Operate

> Production first. Read before you write. Verify, don't assume.

Every change gets investigated read-only before anything is touched. Every fix gets proven, not just applied, with hard evidence (not "it should work now"). When a root cause is still a hypothesis, I treat it as one, until it isn't.

<br/>

## Tech Stack

<p align="center">
<b>Infra & Orchestration</b><br/>
<img alt="Linux" src="https://img.shields.io/badge/linux%20-%23FCC624.svg?&style=for-the-badge&logo=linux&logoColor=black" style="margin:2px;"/>
<img alt="Kubernetes" src="https://img.shields.io/badge/kubernetes%20-%23326CE5.svg?&style=for-the-badge&logo=kubernetes&logoColor=white" style="margin:2px;"/>
<img alt="Docker" src="https://img.shields.io/badge/docker%20-%232496ED.svg?&style=for-the-badge&logo=docker&logoColor=white" style="margin:2px;"/>
<img alt="HAProxy" src="https://img.shields.io/badge/haproxy%20-%23106DA9.svg?&style=for-the-badge&logo=haproxy&logoColor=white" style="margin:2px;"/>
<img alt="Nginx" src="https://img.shields.io/badge/nginx%20-%23009639.svg?&style=for-the-badge&logo=nginx&logoColor=white" style="margin:2px;"/>
</p>

<p align="center">
<b>Automation & IaC</b><br/>
<img alt="Ansible" src="https://img.shields.io/badge/ansible%20-%23EE0000.svg?&style=for-the-badge&logo=ansible&logoColor=white" style="margin:2px;"/>
<img alt="Terraform" src="https://img.shields.io/badge/terraform%20-%23623CE4.svg?&style=for-the-badge&logo=terraform&logoColor=white" style="margin:2px;"/>
<img alt="Bash" src="https://img.shields.io/badge/bash%20-%234EAA25.svg?&style=for-the-badge&logo=gnubash&logoColor=white" style="margin:2px;"/>
<img alt="Python" src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white" style="margin:2px;"/>
</p>

<p align="center">
<b>Observability & Monitoring</b><br/>
<img alt="Prometheus" src="https://img.shields.io/badge/prometheus%20-%23E6522C.svg?&style=for-the-badge&logo=prometheus&logoColor=white" style="margin:2px;"/>
<img alt="Grafana" src="https://img.shields.io/badge/grafana%20-%23F46800.svg?&style=for-the-badge&logo=grafana&logoColor=white" style="margin:2px;"/>
<img alt="Zabbix" src="https://img.shields.io/badge/zabbix%20-%23D40000.svg?&style=for-the-badge&logo=zabbix&logoColor=white" style="margin:2px;"/>
</p>

<p align="center">
<b>Version Control</b><br/>
<img alt="Git" src="https://img.shields.io/badge/git%20-%23F05033.svg?&style=for-the-badge&logo=git&logoColor=white" style="margin:2px;"/>
<img alt="GitHub" src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white" style="margin:2px;"/>
</p>

<br/>

<div align="center">

**Open to connecting with other infra/SRE folks. Reach out anytime.**

</div>
