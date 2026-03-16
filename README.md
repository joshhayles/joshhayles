# Hey, I'm Josh

I'm a Solutions Engineer II at [Datadog](https://www.datadoghq.com/), focused on Kubernetes, containers, and cloud infrastructure. I got into tech at 40 through Flatiron School's software engineering bootcamp. Before that, I spent 15 years in real estate — that background ended up shaping what I build.

---

## What I'm Building

### [Tax Corrector](https://www.taxcorrector.com) — Property Tax Protest SaaS

Texas homeowners get overassessed on property taxes every year. Most don't protest because the process is intimidating, and hiring an attorney costs $1,000+. I built Tax Corrector to solve that — a homeowner enters their address, gets a professional PDF report with comparable home analysis for $27, and takes it to their county to protest.

| Metric | Value |
|--------|-------|
| Homeowners helped | 56+ |
| Protest success rate | 91% |
| Evaluation → purchase conversion | 87% |
| Average tax savings per customer | $900+ |

Under the hood it's async — Celery task chains handle scraping, PDF generation, and payment webhooks through EventBridge and SQS. I built it solo, using AI throughout. (Private repo.)

<details>
<summary><b>Full stack</b></summary>

Django · Python · PostgreSQL (AWS RDS) · Celery + SQS · ReportLab · Stripe · AWS ECS Fargate · S3 · CloudFront · Lambda · EventBridge · GitHub Actions (OIDC) · HTMX · AWS SES · Mailchimp

</details>

---

### [KaI](https://github.com/joshhayles/KaI) — Knowledge as Infrastructure

KaI is a structured context system for AI collaboration. It gives your AI a foundation that carries forward between sessions — your goals, your decisions, what you've both learned — and loads what's relevant instead of everything at once.

It includes collaboration principles, structured project tracking, skill progression, and a messaging layer between Claude instances. I run three of them across three repos, each with different focus areas. The [repo](https://github.com/joshhayles/KaI) has the full breakdown.

It's one approach to a problem a lot of people seem to be hitting. I don't know if it's the best approach, but it's been working for me and I wanted to share it.

---

## Datadog

I help customers instrument, monitor, and debug containerized infrastructure. Spending a lot of time reading Datadog Agent source code in Go and digging into Kubernetes internals to understand the systems I support at a deeper level.

I also use Tax Corrector as an observability sandbox — instrumenting my own production app with the same tools I help customers use.

**Cert:** AWS Certified Cloud Practitioner (2024)

---

## Get in Touch

- [LinkedIn](https://www.linkedin.com/in/joshhayles/)
- [GitHub](https://github.com/joshhayles)
- [joshhayles07@gmail.com](mailto:joshhayles07@gmail.com)
- Colorado Springs, CO
