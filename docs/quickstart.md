# Quickstart

Swapping to CarbonRunner in three simple steps.

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
