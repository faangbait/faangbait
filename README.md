## Hi there, I'm faangbait 👋

I'm an infrastructure engineer who dabbles in Rust, Go, and Markdown.

I build platforms: multi-cluster Kubernetes and OpenShift fleets, Terraform and Ansible automation, GitOps pipelines, and the observability that keeps them honest. I like boring, stable foundations (RHEL/UBI, Rocky, declarative everything) and tooling that makes the secure path the easy path.

Before I wrote infrastructure code, I built hardware: wireless industrial controls, sensors, and firmware-adjacent gadgets. That's why my repos still contain Raspberry Pi and ESP projects.

### What I'm up to

* 🌱 **[Seedling.cv](https://seedling.cv)** — building an AI application system that scores job postings against a full work history, tailors a resume per role, and renders a submission-ready PDF. Zero-trust LLM pipeline, schema-validated outputs, and a bounded-embellishment policy with an audit trail.
* 📦 Making devcontainers that treat AI agents as first-class (and sandboxed) citizens, built on UBI 10.
* 🖥️ Running a bare-metal Kubernetes cluster on Rocky Linux, fully declarative and hardened toward NSA/CISA guidance.

### What I do

* **Platform engineering** — multi-cluster OpenShift/Kubernetes, Hive-style fleet management, single-pane-of-glass control planes (Django + OIDC), GitOps provisioning with Terraform Cloud and GitHub Actions
* **Observability** — Prometheus, Thanos, Alertmanager, and Grafana at the scale of hundreds of clusters; recording rules, cardinality control, and incident command
* **Security and compliance** — SOC 2 programs, AWS Security Hub / Config / GuardDuty, least-privilege IAM, and a habit of treating every input as untrusted
* **Upstream contributions** — bug fixes and docs to Prometheus, Kubernetes, and several Ansible collections
* **CTFs** — I enjoy them enough to have written [`libctf`](https://github.com/faangbait/libctf), extended pwntools helpers

### Projects

A few things I've built and keep maintaining:

| Project | What it is | Language | Last commit |
| --- | --- | --- | --- |
| [**devcontainers**](https://github.com/faangbait/devcontainers) | Not-your-ordinary devcontainers: UBI 10 base, layered for fast builds, sandboxed agents with persistent credentials | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) | ![](https://img.shields.io/github/last-commit/faangbait/devcontainers?style=flat-square&labelColor=343b41) |
| [**dnf-features**](https://github.com/faangbait/dnf-features) | Dev Container Features for RHEL/UBI (`dnf` and `microdnf`), including a rootless `secure-containers` option | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) | ![](https://img.shields.io/github/last-commit/faangbait/dnf-features?style=flat-square&labelColor=343b41) |
| [**cluster**](https://github.com/faangbait/cluster) | Bare-metal Kubernetes runbook on Rocky Linux: BGP via MetalLB, GlusterFS, Calico, rootless containers | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) | ![](https://img.shields.io/github/last-commit/faangbait/cluster?style=flat-square&labelColor=343b41) |
| [**agent-skills**](https://github.com/faangbait/agent-skills) | General-purpose skills for AI agents: better responses for fewer tokens | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) | ![](https://img.shields.io/github/last-commit/faangbait/agent-skills?style=flat-square&labelColor=343b41) |
| [**gnome-alertmanager**](https://github.com/faangbait/gnome-alertmanager) | Prometheus Alertmanager alerts as GNOME desktop notifications; stdlib-only Python daemon | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | ![](https://img.shields.io/github/last-commit/faangbait/gnome-alertmanager?style=flat-square&labelColor=343b41) |
| [**fieldnotes**](https://github.com/faangbait/fieldnotes) | A single Rust binary that serves blog-style Markdown content: no database, no filesystem | ![Rust](https://img.shields.io/badge/-Rust-ce412B?style=flat-square&logo=rust&logoColor=white) | ![](https://img.shields.io/github/last-commit/faangbait/fieldnotes?style=flat-square&labelColor=343b41) |
| [**markdownify-hcl**](https://github.com/faangbait/markdownify-hcl) | Minimal highlight.js grammar for HCL / Terraform: one file, no build step | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ![](https://img.shields.io/github/last-commit/faangbait/markdownify-hcl?style=flat-square&labelColor=343b41) |

### My toolbox

<p>
  <img alt="Rust" src="https://img.shields.io/badge/-Rust-ce412B?style=flat-square&logo=rust&logoColor=white" />
  <img alt="Go" src="https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="Django" src="https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="Bash" src="https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img alt="Terraform" src="https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img alt="Ansible" src="https://img.shields.io/badge/-Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" />
  <img alt="Kubernetes" src="https://img.shields.io/badge/-Kubernetes-326ce5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img alt="OpenShift" src="https://img.shields.io/badge/-OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white" />
  <img alt="Helm" src="https://img.shields.io/badge/-Helm-091C84?style=flat-square&logo=helm&logoColor=white" />
  <img alt="Prometheus" src="https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img alt="Grafana" src="https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img alt="AWS" src="https://img.shields.io/badge/-AWS-232F3E?style=flat-square" />
  <img alt="Red Hat" src="https://img.shields.io/badge/-Red_Hat-EE0000?style=flat-square&logo=redhat&logoColor=white" />
  <img alt="Rocky Linux" src="https://img.shields.io/badge/-Rocky_Linux-10B981?style=flat-square&logo=rockylinux&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>
