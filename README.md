<p align="center">
  <a href="https://bayplan.dev"><img src="images/logo.png" width="72" alt="Bayplan logo"></a>
</p>

<h1 align="center">Bayplan</h1>

<p align="center">
  <b>A fast desktop app for Amazon ECS.</b><br>
  Every cluster, service and task across your AWS accounts and regions, in one window.
</p>

<p align="center">
  <a href="https://bayplan.dev">Website</a> ·
  <a href="https://demo.bayplan.dev">Live demo</a> ·
  <a href="https://bayplan.dev/blog">Blog</a> ·
  <a href="https://bayplan.dev/tools">Free ECS tools</a>
</p>

---

Bayplan replaces clicking through the AWS console region by region. It reads your existing AWS profiles and SSO logins, talks to AWS directly from your machine and never sends your credentials or data anywhere else. Available for macOS, Windows and Linux.

### See what needs attention

The dashboard sums up every cluster and lists what is broken right now: failed deployments, crashing tasks and services that are short on tasks.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/dark-dashboard.png">
  <img src="images/light-dashboard.png" alt="Bayplan dashboard with cluster, service and task health and a list of issues">
</picture>

### Metrics and logs where you need them

CPU and memory per service, used against reserved, and CloudWatch logs from all tasks in one view with live follow and filtering.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/dark-metrics.png">
  <img src="images/light-metrics.png" alt="Service metrics with CPU and memory utilization charts">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/dark-logs.png">
  <img src="images/light-logs.png" alt="Service logs from all tasks with level highlighting">
</picture>

### Know what changed

Every deployment of a service on a timeline, with the image and task definition changes that came with it and rollbacks marked.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/dark-history.png">
  <img src="images/light-history.png" alt="Deployment history of a service with image version changes">
</picture>

### Follow traffic to your tasks

From load balancer to listener, rule, target group, service and healthy or draining target, drawn as one map per cluster.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/dark-network.png">
  <img src="images/light-network.png" alt="Network map from load balancers to ECS service targets">
</picture>

### Open a shell in any container

ECS Exec built in: pick a running container and get a terminal, without the AWS CLI or the Session Manager plugin.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/dark-exec.png">
  <img src="images/light-exec.png" alt="Interactive ECS Exec shell in a running Fargate task">
</picture>

### Find anything

Search clusters, services, tasks and task definitions across all accounts and regions with <kbd>Ctrl</kbd> <kbd>K</kbd>.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/dark-search.png">
  <img src="images/light-search.png" alt="Global search across services, task definitions and tasks">
</picture>

---

### Open source from Bayplan

- [awesome-ecs](https://github.com/bayplan-dev/awesome-ecs) - A curated list of tools, guides and resources for Amazon ECS and AWS Fargate.

<sub>Screenshots use demo data. Bayplan is not affiliated with Amazon Web Services.</sub>
