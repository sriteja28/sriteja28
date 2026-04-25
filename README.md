# 👋 Sriteja Kattamuru

Principal / Staff IC at ScyllaDB. 12+ years building production
distributed systems on Kubernetes, AWS, and multi-cloud. Currently
extending that foundation into AI infrastructure — see
[production-llm-platform](https://github.com/sriteja28/production-llm-platform).

## 🚀 What I'm building

[**production-llm-platform**](https://github.com/sriteja28/production-llm-platform)
— a multi-tenant LLM serving platform built for reasoning-and-agent
workloads: scheduling, caching, and cost control when output length
is unpredictable (reasoning traces from 10 to 30,000+ tokens) and KV
state persists across hundreds of agent turns. Backend-agnostic core
(vLLM + MLX-LM behind a pluggable interface), anchored to **Spider**
— a Glean-style internal-team knowledge agent where each tenant is
an org and agents reason across Slack, Confluence, Drive, and GitHub
with per-org ACL isolation. Live build over ~6 months, milestone by
milestone, with deliberate production failures debugged in public.

## 🏗️ Selected past work

- [**eks-three-tier-aws-infra**](https://github.com/sriteja28/eks-three-tier-aws-infra)
  — Terraform + Helm reference for self-managed EKS on AWS with a
  three-tier network topology (public / private / database) supporting
  stateful workloads like Jira Datacenter. Built during my Atlassian
  Jira Cloud Enterprise work; mirrors the production architecture I
  was operating at scale.

## Background

- **ScyllaDB (current).** Platform engineering for Scylla Cloud —
  CD orchestration with Argo CD, multi-cloud rollouts, observability.
- **Atlassian.** Founding infrastructure engineer for Jira Cloud
  Enterprise on AWS EKS. Deep Kubernetes, GitOps, durable workflows.
- **AI foundations.** Karpathy's Neural Networks: Zero to Hero,
  PagedAttention, FlashAttention, hands-on with vLLM and MLX-LM.

## 📫 Reach me

- Email: sritejakattamuru28@gmail.com
- LinkedIn: [linkedin.com/in/sriteja-kattamuru-38026a67](https://www.linkedin.com/in/sriteja-kattamuru-38026a67)
- GitHub: [@sriteja28](https://github.com/sriteja28)
