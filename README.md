# 🚀 github-actions-ci-cd-demo

**Modern CI/CD pipelines for infrastructure & applications** — part of the DevEmpire2026 revival.

This repo demonstrates end-to-end automation using GitHub Actions for testing, building, and deploying infrastructure and code.

## ⚡ What’s Inside
- Multi-environment deployment workflows
- Terraform plan/apply automation
- Docker build & push to ECR
- Automated testing (Terraform validate, tflint, checkov)
- Slack/Teams notifications on success/failure
- OIDC authentication (no long-lived credentials)

## 🔧 Tech Stack
- GitHub Actions
- Terraform
- Docker
- AWS (ECR, ECS, Lambda)
- OIDC + IAM Roles

## 🚀 Quick Start
```bash
git clone https://github.com/Lluminatarion-8431/github-actions-ci-cd-demo.git
cd github-actions-ci-cd-demo
# Push to trigger workflow
```

## 📈 Workflow Highlights
- `.github/workflows/deploy.yml` — Full IaC pipeline
- Security scanning on every PR
- Environment promotion (dev → staging → prod)

## 🎯 Next Steps
- Add ArgoCD / Flux for GitOps
- Implement canary deployments
- Add cost optimization checks
- Integrate with ServiceNow / Jira

**Fast. Secure. Repeatable. This is how modern teams ship.**

---

🔥 Part of [DevEmpire2026](https://github.com/Lluminatarion-8431/DevEmpire2026) | Network Engineering & DevOps Portfolio