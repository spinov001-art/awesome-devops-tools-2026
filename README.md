# Awesome DevOps Tools 2026 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the best DevOps tools, platforms, and resources for 2026. Updated regularly.

## Contents

- [CI/CD](#cicd)
- [Infrastructure as Code](#infrastructure-as-code)
- [Container Orchestration](#container-orchestration)
- [Monitoring & Observability](#monitoring--observability)
- [Cloud Platforms](#cloud-platforms)
- [Configuration Management](#configuration-management)
- [Secret Management](#secret-management)
- [GitOps](#gitops)
- [Service Mesh](#service-mesh)
- [Logging](#logging)
- [Artifact Management](#artifact-management)
- [Incident Management](#incident-management)
- [Cost Optimization](#cost-optimization)
- [Developer Platforms](#developer-platforms)
- [AI for DevOps](#ai-for-devops)

---

## CI/CD

- [GitHub Actions](https://github.com/features/actions) — Native CI/CD for GitHub repos with 6000+ marketplace actions
- [GitLab CI](https://docs.gitlab.com/ee/ci/) — Built-in CI/CD with Auto DevOps and pipeline visualization
- [CircleCI](https://circleci.com) — Cloud-native CI/CD with Docker layer caching and parallelism
- [Jenkins](https://jenkins.io) — Extensible automation server with 1800+ plugins
- [Buildkite](https://buildkite.com) — Hybrid CI/CD — agents run on your infra, UI in the cloud
- [Dagger](https://dagger.io) — Programmable CI/CD engine running pipelines in containers
- [Woodpecker CI](https://woodpecker-ci.org) — Lightweight CI engine, fork of Drone
- [Earthly](https://earthly.dev) — Makefile + Dockerfile = reproducible builds
- [Depot](https://depot.dev) — 20x faster Docker builds with managed remote builders
- [Harness](https://harness.io) — AI-powered delivery platform with cost governance
- [Spacelift](https://spacelift.io) — CI/CD for infrastructure (Terraform, Pulumi, CloudFormation)
- [Tekton](https://tekton.dev) — Kubernetes-native CI/CD building blocks
- [Semaphore](https://semaphoreci.com) — High-performance CI/CD with test parallelism

## Infrastructure as Code

- [Terraform](https://terraform.io) — Multi-cloud IaC with HCL, 3000+ providers
- [OpenTofu](https://opentofu.org) — Open-source Terraform fork (Linux Foundation)
- [Pulumi](https://pulumi.com) — IaC using real programming languages (Python, TypeScript, Go)
- [Crossplane](https://crossplane.io) — Kubernetes-native IaC using CRDs
- [CDK for Terraform](https://developer.hashicorp.com/terraform/cdktf) — Write Terraform with TypeScript/Python
- [AWS CDK](https://aws.amazon.com/cdk/) — Define AWS resources in TypeScript, Python, Java, Go
- [Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/) — Azure's domain-specific IaC language
- [Winglang](https://winglang.io) — Cloud-oriented programming language for IaC + runtime
- [SST](https://sst.dev) — Build full-stack apps on AWS with live Lambda development
- [Ansible](https://ansible.com) — Agentless automation for config, deployment, orchestration

## Container Orchestration

- [Kubernetes](https://kubernetes.io) — Industry standard container orchestration
- [Docker Swarm](https://docs.docker.com/engine/swarm/) — Simple container orchestration built into Docker
- [Nomad](https://nomadproject.io) — Flexible workload orchestrator from HashiCorp
- [K3s](https://k3s.io) — Lightweight Kubernetes for edge and IoT
- [Talos Linux](https://talos.dev) — Minimal, immutable Linux OS designed for Kubernetes
- [KubeEdge](https://kubeedge.io) — Extend Kubernetes to edge devices
- [vCluster](https://vcluster.com) — Virtual Kubernetes clusters inside real clusters
- [Rancher](https://rancher.com) — Multi-cluster Kubernetes management
- [OpenShift](https://openshift.com) — Enterprise Kubernetes platform by Red Hat

## Monitoring & Observability

- [Prometheus](https://prometheus.io) — Time-series metrics with PromQL
- [Grafana](https://grafana.com) — Visualization dashboards for any data source
- [Datadog](https://datadoghq.com) — Full-stack observability platform (APM, logs, metrics)
- [New Relic](https://newrelic.com) — All-in-one observability with free 100GB/month
- [OpenTelemetry](https://opentelemetry.io) — Vendor-neutral observability framework
- [Jaeger](https://jaegertracing.io) — Distributed tracing for microservices
- [Signoz](https://signoz.io) — Open-source alternative to Datadog
- [Uptrace](https://uptrace.dev) — Open-source APM with distributed tracing
- [VictoriaMetrics](https://victoriametrics.com) — High-performance time-series database
- [Cilium](https://cilium.io) — eBPF-based networking, observability, and security
- [Pixie](https://px.dev) — Auto-instrumented observability for Kubernetes using eBPF

## Cloud Platforms

- [AWS](https://aws.amazon.com) — Largest cloud provider, 200+ services
- [Google Cloud](https://cloud.google.com) — Strong in data/ML, Kubernetes-native
- [Azure](https://azure.microsoft.com) — Microsoft ecosystem, enterprise integration
- [DigitalOcean](https://digitalocean.com) — Simple cloud for developers and SMBs
- [Hetzner](https://hetzner.com) — Price-performance leader in EU
- [Fly.io](https://fly.io) — Run apps close to users globally (edge)
- [Railway](https://railway.app) — Deploy from GitHub in seconds
- [Render](https://render.com) — Modern cloud for teams (auto-deploy, managed DBs)
- [Vercel](https://vercel.com) — Frontend & serverless deployment optimized for Next.js
- [Cloudflare Workers](https://workers.cloudflare.com) — Edge compute on Cloudflare's network

## Configuration Management

- [Ansible](https://ansible.com) — Agentless, YAML-based automation
- [Chef](https://chef.io) — Infrastructure automation with Ruby DSL
- [Puppet](https://puppet.com) — Model-driven configuration management
- [Salt](https://saltproject.io) — Event-driven automation at scale
- [CFEngine](https://cfengine.com) — Lightweight, autonomous config management

## Secret Management

- [HashiCorp Vault](https://vaultproject.io) — Secret lifecycle management, encryption as a service
- [AWS Secrets Manager](https://aws.amazon.com/secrets-manager/) — Rotate and manage secrets in AWS
- [Infisical](https://infisical.com) — Open-source secret management for teams
- [Doppler](https://doppler.com) — Universal secrets platform for any stack
- [SOPS](https://github.com/getsops/sops) — Encrypt files with AWS KMS, GCP KMS, PGP
- [External Secrets Operator](https://external-secrets.io) — Sync secrets from vaults to Kubernetes
- [CyberArk Conjur](https://conjur.org) — Enterprise secrets management

## GitOps

- [ArgoCD](https://argoproj.github.io/cd/) — Declarative GitOps for Kubernetes
- [Flux](https://fluxcd.io) — GitOps toolkit for Kubernetes (CNCF)
- [Weave GitOps](https://weave.works) — Enterprise GitOps platform
- [Codefresh](https://codefresh.io) — GitOps + CI/CD combined platform
- [Kargo](https://kargo.io) — Multi-stage GitOps promotion for Kubernetes

## Service Mesh

- [Istio](https://istio.io) — Most adopted service mesh for Kubernetes
- [Linkerd](https://linkerd.io) — Ultralight service mesh (CNCF graduated)
- [Consul Connect](https://consul.io) — Service mesh with service discovery by HashiCorp
- [Cilium Service Mesh](https://cilium.io) — eBPF-based service mesh (no sidecars)
- [Kuma](https://kuma.io) — Universal service mesh by Kong

## Logging

- [ELK Stack](https://elastic.co/elk-stack) — Elasticsearch + Logstash + Kibana
- [Loki](https://grafana.com/loki) — Log aggregation by Grafana Labs (Prometheus for logs)
- [Fluentd](https://fluentd.org) — Unified logging layer (CNCF graduated)
- [Vector](https://vector.dev) — High-performance observability pipeline
- [Graylog](https://graylog.org) — Open-source log management

## Artifact Management

- [JFrog Artifactory](https://jfrog.com) — Universal artifact repository
- [Nexus Repository](https://sonatype.com/nexus) — Manage binaries and build artifacts
- [Harbor](https://goharbor.io) — Cloud-native container registry (CNCF)
- [GitHub Packages](https://github.com/features/packages) — Package hosting on GitHub
- [GHCR](https://ghcr.io) — GitHub Container Registry

## Incident Management

- [PagerDuty](https://pagerduty.com) — Incident response and on-call management
- [OpsGenie](https://opsgenie.com) — Alert management by Atlassian
- [incident.io](https://incident.io) — Modern incident management for Slack
- [Rootly](https://rootly.com) — AI-powered incident management
- [Statuspage](https://statuspage.io) — Communicate status to users

## Cost Optimization

- [Infracost](https://infracost.io) — Cloud cost estimates in pull requests
- [Kubecost](https://kubecost.com) — Kubernetes cost monitoring
- [Vantage](https://vantage.sh) — Multi-cloud cost transparency
- [CAST AI](https://cast.ai) — Kubernetes cost optimization with autoscaling
- [Spot.io](https://spot.io) — Spot instance management by NetApp

## Developer Platforms

- [Backstage](https://backstage.io) — Developer portal by Spotify (CNCF)
- [Port](https://getport.io) — Internal developer portal
- [Humanitec](https://humanitec.com) — Platform engineering reference architecture
- [Qovery](https://qovery.com) — Internal deployment platform on your cloud
- [Bunnyshell](https://bunnyshell.com) — Environments as a Service

## AI for DevOps

- [K8sGPT](https://k8sgpt.ai) — AI-powered Kubernetes diagnostics
- [Kubiya](https://kubiya.ai) — AI teammates for DevOps workflows
- [Harness AIDA](https://harness.io) — AI-assisted delivery and error analysis
- [Codefresh AI](https://codefresh.io) — AI-powered pipeline optimization
- [Kosli](https://kosli.com) — DevOps change forensics and compliance

---

## Related

- [Awesome Security Tools 2026](https://github.com/spinov001-art/awesome-security-tools-2026) — 150+ cybersecurity tools
- [awesome-ai-tools-2026](https://github.com/spinov001-art/awesome-ai-tools-2026) — 150+ AI tools, LLMs, agents
- [awesome-mcp-tools-2026](https://github.com/spinov001-art/awesome-mcp-tools-2026) — 130+ MCP servers & clients
- [awesome-api-tools-2026](https://github.com/spinov001-art/awesome-api-tools-2026) — 120+ API development tools
- [awesome-web-scraping-2026](https://github.com/spinov001-art/awesome-web-scraping-2026) — 130+ web scraping tools, frameworks & proxies
- [awesome-cli-tools-2026](https://github.com/spinov001-art/awesome-cli-tools-2026) — 50+ modern CLI tools
- [awesome-python-devtools-2026](https://github.com/spinov001-art/awesome-python-devtools-2026) — 80+ Python developer tools
- [awesome-free-research-apis](https://github.com/spinov001-art/awesome-free-research-apis) — 30+ free academic APIs

## Contributing

PRs welcome! Please ensure your suggestion is:
- Actively maintained (updated in last 12 months)
- Well-documented
- Genuinely useful for DevOps practitioners

## Author

**Aleksej Spinov** — AI & Automation Engineer
- 🌐 [Portfolio](https://spinov001-art.github.io)
- 💻 [GitHub](https://github.com/spinov001-art) — 270+ open source repos
- 📧 spinov001@gmail.com

## License

CC0 1.0 Universal
