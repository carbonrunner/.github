# Runner Types

CarbonRunner runners are faster, 25% cheaper and 90% less than carbon emissions then GitHub-hosted runners.

```
jobs:
  deploy:
-   runs-on: ubuntu-latest
+   runs-on: carbonrunner-2vcpu-ubuntu-latest
```

## Intel/AMD

Update your workflow’s runs-on line to use CarbonRunner. We’ll pick up the PR checks automatically — that run will be the first you see in the dashboard.

We only use the fastest and latest servers for performance and price.

| vCPU Count                          | Memory      | Storage          | Price      |
| ----------------------------------- | ----------- | ---------------- | ---------- |
| `carbonrunner-1vcpu-ubuntu-latest`  | 4 GiB RAM   | 40 GiB SSD disk  | $0.003/min |
| `carbonrunner-2vcpu-ubuntu-latest`  | 8 GiB RAM   | 80 GiB SSD disk  | $0.006/min |
| `carbonrunner-4vcpu-ubuntu-latest`  | 16 GiB RAM  | 80 GiB SSD disk  | $0.012/min |
| `carbonrunner-8vcpu-ubuntu-latest`  | 32 GiB RAM  | 160 GiB SSD disk | $0.024/min |
| `carbonrunner-16vcpu-ubuntu-latest` | 64 GiB RAM  | 160 GiB SSD disk | $0.048/min |
| `carbonrunner-32vcpu-ubuntu-latest` | 128 GiB RAM | 160 GiB SSD disk | $0.096/min |
