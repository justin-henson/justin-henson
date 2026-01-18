# Justin Henson — Cloud / DevOps Portfolio (NZ & AU-ready)

I build production-minded cloud infrastructure with **Terraform**, focusing on **security, operability, and repeatable demos** (create → verify → destroy).
I’m targeting **Cloud / DevOps / Infrastructure** roles in **New Zealand and Australia**.

## Start here (fastest review path)

1. **Portfolio index (recommended order + narrative):** [https://github.com/justin-henson/nz-sponsor-portfolio](https://github.com/justin-henson/nz-sponsor-portfolio)
2. **Hands-on AWS Terraform baseline (core infra):** [https://github.com/justin-henson/nz-cloud-baseline-aws](https://github.com/justin-henson/nz-cloud-baseline-aws)
3. **Ops / SRE runbooks + templates (operate & improve):** [https://github.com/justin-henson/nz-ops-runbooks](https://github.com/justin-henson/nz-ops-runbooks)

## What you’ll find in my repos

* Clear “**what/why**” up top (what it demonstrates + tradeoffs)
* **Architecture diagrams** (Mermaid)
* **Proof steps** you can run to verify it works
* **Run / Destroy** commands for clean, repeatable demos
* **Security + Cost notes** (what’s locked down, what drives spend)

---

## Featured projects

### 1) nz-cloud-baseline-aws — AWS baseline with Terraform (VPC, ALB, private EC2 via SSM)

**Why it matters:** demonstrates real-world patterns: controlled ingress, private compute (**no SSH**), and ops-minded defaults you can explain in an interview.

**Highlights**

* VPC with public/private subnets across 2 AZs
* ALB → Target Group → private instance (port 8080)
* SSM access (no inbound SSH)
* Repeatable workflow: create → verify → destroy

➡️ Repo: [https://github.com/justin-henson/nz-cloud-baseline-aws](https://github.com/justin-henson/nz-cloud-baseline-aws)

### 2) nz-ops-runbooks — Operational runbooks & templates (incident, change, DR)

**Why it matters:** shows I think beyond “deploy” into **operate + recover + improve**.

**Highlights**

* Incident response + postmortem templates
* Change management checklists
* DR planning notes + operational workflows
* Small automation helpers where useful

➡️ Repo: [https://github.com/justin-henson/nz-ops-runbooks](https://github.com/justin-henson/nz-ops-runbooks)

### 3) nz-sponsor-portfolio — Sponsor-ready portfolio index (what to review + order)

**Why it matters:** makes it easy to evaluate my work quickly without guessing where to start.

**Highlights**

* Recommended review path
* One-page story tying repos to job responsibilities
* Architecture overview + quick verification links

➡️ Repo: [https://github.com/justin-henson/nz-sponsor-portfolio](https://github.com/justin-henson/nz-sponsor-portfolio)

---

## Tech I use (and why)

* **Terraform** (repeatable infra, clean diffs, predictable destroy)
* **AWS** (VPC networking, ALB, IAM, SSM, VPC endpoints)
* **Linux + CLI** (debugging, automation, operational workflows)
* **Ops practices** (runbooks, incident/postmortems, DR thinking)

## Notes on cost / safety for demos

Some AWS demos can incur charges while running (especially **ALBs** and **VPC interface endpoints**).
Each repo is designed so resources can be **destroyed cleanly right after verification**.

---

## Contact
- LinkedIn: **https://www.linkedin.com/in/justin-henson/**
- Email: **justin.henson@pm.me**

If you’re hiring for NZ/AU cloud, DevOps, or infrastructure roles: the **Start here** section above is the fastest way to review my work.

