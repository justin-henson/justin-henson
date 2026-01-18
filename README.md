# Justin Henson — Cloud / DevOps / Infrastructure

I build and operate AWS infrastructure with Terraform—secure defaults, CI/CD automation, Kubernetes workloads, and monitoring that ties back to runbooks. Everything here is working code you can validate.

**What I can do:** provision cloud infrastructure, automate deployments, run Kubernetes clusters, set up monitoring with SLOs, and write the runbooks so on-call isn't chaos.

## AU/NZ availability

- Based in Texas (Central Time, CT).
- **NZ (Auckland/Wellington):** I can overlap **12:00pm–4:00pm NZT** (typically Mon–Fri).
- **AU (Sydney/Melbourne):** I can overlap **8:00am–2:00pm AEDT** (typically Mon–Fri).
- Interview windows: Weekdays **6:00–10:00pm CT**, weekends by arrangement.
- Work status: Targeting roles in Australia and New Zealand; open to sponsorship and relocation.
- Role preference: Cloud / DevOps / Infrastructure (Terraform, AWS, Kubernetes, CI/CD, monitoring).

---

## **Start here (fastest review path)**

Recommended review order — each repo builds on the last:

1. **Portfolio index** — context, narrative, and reviewer path
   ➜ [au-nz-sponsor-portfolio](https://github.com/justin-henson/au-nz-sponsor-portfolio)

2. **AWS Terraform baseline** — core cloud infra (VPC, ALB, private EC2 via SSM)
   ➜ [au-nz-cloud-baseline-aws](https://github.com/justin-henson/au-nz-cloud-baseline-aws)

3. **CI/CD pipeline** — GitHub Actions with Terraform plan/apply, drift detection, and notifications
   ➜ [au-nz-cicd-pipeline](https://github.com/justin-henson/au-nz-cicd-pipeline)

4. **Kubernetes baseline** — EKS cluster with security-hardened workloads, Pod Security Standards, IRSA
   ➜ [au-nz-k8s-baseline-eks](https://github.com/justin-henson/au-nz-k8s-baseline-eks)

5. **Observability stack** — CloudWatch alarms, Prometheus/Grafana dashboards, SLOs, and alert routing
   ➜ [au-nz-observability-stack](https://github.com/justin-henson/au-nz-observability-stack)

6. **Ops / SRE runbooks** — incident response, postmortems, change management, and DR templates
   ➜ [au-nz-ops-runbooks](https://github.com/justin-henson/au-nz-ops-runbooks)

---

## **How it all connects**

```
Build (Terraform) → Deploy (CI/CD) → Run (EKS) → Monitor (Observability) → Respond (Runbooks)
     [2]               [3]            [4]              [5]                      [6]
```

The repos aren't standalone demos — they represent a full infrastructure lifecycle. The CI/CD pipeline deploys the Terraform that provisions the EKS cluster. The observability stack monitors that cluster. When alerts fire, the runbooks tell you what to do. Each repo cross-references the others.

---

## **Fast proof (60 seconds)**

* **Infrastructure:** open `au-nz-cloud-baseline-aws` and check the Terraform — VPC, ALB, private EC2, no SSH
* **CI/CD:** open `au-nz-cicd-pipeline` and look at the GitHub Actions workflows — plan on PR, apply on merge, scheduled drift detection
* **Kubernetes:** open `au-nz-k8s-baseline-eks` — EKS with Pod Security Standards enforcing restricted mode
* **Monitoring:** open `au-nz-observability-stack` — CloudWatch alarms, Prometheus alert rules, SLO definitions with error budgets
* **Ops mindset:** skim `au-nz-ops-runbooks` for incident response, postmortems, and DR templates

---

## **Featured projects**

### **1) au-nz-sponsor-portfolio — BEGIN HERE**

**Why it matters:** removes guesswork for interviewers by providing review order and narrative

➡ [https://github.com/justin-henson/au-nz-sponsor-portfolio](https://github.com/justin-henson/au-nz-sponsor-portfolio)

---

### **2) au-nz-cloud-baseline-aws — AWS baseline with Terraform**

**Why it matters:** demonstrates controlled ingress, private compute (no SSH), and ops-minded defaults

➡ [https://github.com/justin-henson/au-nz-cloud-baseline-aws](https://github.com/justin-henson/au-nz-cloud-baseline-aws)

---

### **3) au-nz-cicd-pipeline — CI/CD with GitHub Actions + Terraform**

**Why it matters:** shows automated plan/apply workflow with drift detection — not just `terraform apply`

➡ [https://github.com/justin-henson/au-nz-cicd-pipeline](https://github.com/justin-henson/au-nz-cicd-pipeline)

---

### **4) au-nz-k8s-baseline-eks — EKS Kubernetes baseline**

**Why it matters:** production-ready EKS with security hardening, IRSA, and Pod Security Standards

➡ [https://github.com/justin-henson/au-nz-k8s-baseline-eks](https://github.com/justin-henson/au-nz-k8s-baseline-eks)

---

### **5) au-nz-observability-stack — Monitoring and observability**

**Why it matters:** shows monitoring design, not just dashboards — SLOs, error budgets, alert routing, and runbook-linked alerts

➡ [https://github.com/justin-henson/au-nz-observability-stack](https://github.com/justin-henson/au-nz-observability-stack)

---

### **6) au-nz-ops-runbooks — Ops/SRE runbooks and templates**

**Why it matters:** shows thinking beyond *deploy* into *operate → recover → improve*

➡ [https://github.com/justin-henson/au-nz-ops-runbooks](https://github.com/justin-henson/au-nz-ops-runbooks)

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

## **AU/NZ-friendly**

I'm targeting Cloud / DevOps / Infrastructure roles in **Australia and New Zealand** and can align working hours for AU/NZ overlap.

---

## **Contact**

LinkedIn: [https://www.linkedin.com/in/justin-henson/](https://www.linkedin.com/in/justin-henson/)
Email: [justin.henson@pm.me](mailto:justin.henson@pm.me)

If you're hiring for AU/NZ cloud, DevOps, or infrastructure roles — the **Start here** section above is the fastest way to review my work.

*Built with ☕ for AU/NZ DevOps opportunities*
