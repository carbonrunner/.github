# Welcome

Lets supercharge your GitHub Actions!

Run your GitHub Actions faster, 25% cheaper, and 90% greener. Across AWS, Azure, and GCP. Built for speed, savings, and sustainability, with multi-cloud resilience for unmatched reliability.

## Why CarbonRunner

* ⚡ Greener: Shift workloads to lowest-carbon regions in real time
* 💸 Cheaper: Save on CI/CD minutes and infra
* 🌍 Resilient: Multi-region control + data sovereignty
* 🔒 Enterprise-ready: SAML/SSO, private metadata, patching schedules

## Features 

* 25% cheaper - Across all runner types we're 25% cheaper
* 15% faster - Our Linux builds are 15% faster than default GitHub Actions
* 90% greener - We only run your jobs in low-CO2 regions under 100gCO2/kWh
* Multi-cloud resilience - We run your jobs across AWS, Azure, GCP and Heata clouds for maxiumum resiliance.
* Region preference & control - Decide where your jobs run, with full sovereignty over data and compliance.
* ESG Dashboards - CarbonRunner gives you transparent dashboards and ESG-ready exports out of the box.
* Single-line-code - Swapping your `runs-on` like is super easy. 

## Quickstart 

### 1. Sign in & connect up GitHub

Open the CarbonRunner dashboard and grant the permissions we need to execute your GitHub Action jobs on our carbon-aware infrastructure.

### 2. Update your `runs-on` line

```yml
# .github/workflows/ci.yml

jobs:
  deploy: 
-   runs-on: ubuntu-latest
+   runs-on: carbonrunner-2vcpu-ubuntu-latest
```

### 3. Run your Actions & see the savings.

Trigger a build (or wait for the next one). We auto-route to the cleanest, fastest region.

![GitHub Actions job table showing CO2 savings and cost](https://carbon-runner.imgix.net/jobs-list.png)


## Helpful links

* 🚀 carbonrunner-action — main GitHub Action
* 🛠 carbonrunner-examples — ready-to-use workflows (Node, Python, Go…)
* 📚 [carbonrunner-docs](https://carbonrunner.io/docs/getting-started/welcome) — FAQs, enterprise features, case studies
* 🌐 [Website](https://carbonrunner.io/) — learn more


Join the Journey

💬 Open a Discussion
🐞 Report Issues
📢 Follow us on LinkedIn
