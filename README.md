# Justin Henson — Cloud / DevOps / Infrastructure

I build and operate AWS infrastructure with Terraform—secure defaults, CI/CD automation, Kubernetes workloads, and monitoring that ties back to runbooks. Everything here is working code you can validate.

**What I can do:** provision cloud infrastructure, automate deployments, run Kubernetes clusters, set up monitoring with SLOs, and write the runbooks so on-call isn't chaos.

## Global availability

- Based in Texas (Central Time, CT).
- Flexible working hours to overlap with team timezone.
- Interview windows: Weekdays **6:00–10:00pm CT**, weekends by arrangement.
- Work status: Open to remote opportunities worldwide; open to sponsorship and relocation.
- Role preference: Cloud / DevOps / Infrastructure (Terraform, AWS, Kubernetes, CI/CD, monitoring).

---

## **Start here (fastest review path)**

Recommended review order — each repo builds on the last:

1. **Portfolio index** — context, narrative, and reviewer path
   ➜ [cloud-devops-portfolio](https://github.com/justin-henson/cloud-devops-portfolio)

2. **AWS Terraform baseline** — core cloud infra (VPC, ALB, private EC2 via SSM)
   ➜ [cloud-baseline-aws](https://github.com/justin-henson/cloud-baseline-aws)

3. **CI/CD pipeline** — GitHub Actions with Terraform plan/apply, drift detection, and notifications
   ➜ [cicd-pipeline](https://github.com/justin-henson/cicd-pipeline)

4. **Kubernetes baseline** — EKS cluster with security-hardened workloads, Pod Security Standards, IRSA
   ➜ [k8s-baseline-eks](https://github.com/justin-henson/k8s-baseline-eks)

5. **Observability stack** — CloudWatch alarms, Prometheus/Grafana dashboards, SLOs, and alert routing
   ➜ [observability-stack](https://github.com/justin-henson/observability-stack)

6. **Ops / SRE runbooks** — incident response, postmortems, change management, and DR templates
   ➜ [ops-runbooks](https://github.com/justin-henson/ops-runbooks)

---

## **How it all connects**

```
Build (Terraform) → Deploy (CI/CD) → Run (EKS) → Monitor (Observability) → Respond (Runbooks)
     [2]               [3]            [4]              [5]                      [6]
```

The repos aren't standalone demos — they represent a full infrastructure lifecycle. The CI/CD pipeline deploys the Terraform that provisions the EKS cluster. The observability stack monitors that cluster. When alerts fire, the runbooks tell you what to do. Each repo cross-references the others.

---

## **Fast proof (60 seconds)**

* **Infrastructure:** open `cloud-baseline-aws` and check the Terraform — VPC, ALB, private EC2, no SSH
* **CI/CD:** open `cicd-pipeline` and look at the GitHub Actions workflows — plan on PR, apply on merge, scheduled drift detection
* **Kubernetes:** open `k8s-baseline-eks` — EKS with Pod Security Standards enforcing restricted mode
* **Monitoring:** open `observability-stack` — CloudWatch alarms, Prometheus alert rules, SLO definitions with error budgets
* **Ops mindset:** skim `ops-runbooks` for incident response, postmortems, and DR templates

---

## **Featured projects**

### **1) cloud-devops-portfolio — BEGIN HERE**

**Why it matters:** removes guesswork for interviewers by providing review order and narrative

➡ [https://github.com/justin-henson/cloud-devops-portfolio](https://github.com/justin-henson/cloud-devops-portfolio)

---

### **2) cloud-baseline-aws — AWS baseline with Terraform**

**Why it matters:** demonstrates controlled ingress, private compute (no SSH), and ops-minded defaults

➡ [https://github.com/justin-henson/cloud-baseline-aws](https://github.com/justin-henson/cloud-baseline-aws)

---

### **3) cicd-pipeline — CI/CD with GitHub Actions + Terraform**

**Why it matters:** shows automated plan/apply workflow with drift detection — not just `terraform apply`

➡ [https://github.com/justin-henson/cicd-pipeline](https://github.com/justin-henson/cicd-pipeline)

---

### **4) k8s-baseline-eks — EKS Kubernetes baseline**

**Why it matters:** production-ready EKS with security hardening, IRSA, and Pod Security Standards

➡ [https://github.com/justin-henson/k8s-baseline-eks](https://github.com/justin-henson/k8s-baseline-eks)

---

### **5) observability-stack — Monitoring and observability**

**Why it matters:** shows monitoring design, not just dashboards — SLOs, error budgets, alert routing, and runbook-linked alerts

➡ [https://github.com/justin-henson/observability-stack](https://github.com/justin-henson/observability-stack)

---

### **6) ops-runbooks — Ops/SRE runbooks and templates**

**Why it matters:** shows thinking beyond *deploy* into *operate → recover → improve*

➡ [https://github.com/justin-henson/ops-runbooks](https://github.com/justin-henson/ops-runbooks)

---

## **Skills snapshot**

* **Terraform** — modules, state management, clean diffs, predictable destroy
* **AWS** — VPC, EKS, IAM, ALB, CloudWatch, SSM, KMS, SNS
* **Kubernetes** — EKS, Pod Security Standards, IRSA, Helm, resource management
* **CI/CD** — GitHub Actions, Terraform automation, drift detection, PR workflows
* **Monitoring** — Prometheus, Grafana, CloudWatch, Alertmanager, SLOs/error budgets
* **Ops / SRE** — runbooks, incident response, postmortems, change management, DR
* **Linux + CLI** — debugging, shell scripting, automation

---

## **Open to opportunities worldwide**

I'm targeting Cloud / DevOps / Infrastructure roles and can align working hours for team overlap globally.

---

## **Contact**

LinkedIn: [https://www.linkedin.com/in/justin-henson/](https://www.linkedin.com/in/justin-henson/)
Email: [justin.henson@pm.me](mailto:justin.henson@pm.me)

If you're hiring for cloud, DevOps, or infrastructure roles — the **Start here** section above is the fastest way to review my work.
