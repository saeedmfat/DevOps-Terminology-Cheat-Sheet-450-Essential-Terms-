🧠 DevOps Terminology Cheat Sheet (460+ Essential Terms)

(Compact & Printable Edition – Cloud-Agnostic)

🧩 Core DevOps Concepts

DevOps — Collaboration between Dev & Ops for faster delivery

SDLC — Software Development Life Cycle

Agile — Iterative software development methodology

Scrum — Agile framework using sprints

Kanban — Visual task board method

Lean — Eliminating waste, maximizing value

Waterfall — Linear software development approach

CI — Continuous Integration of code

CD — Continuous Delivery/Deployment

Pipeline — Automated CI/CD process chain

Artifact — Built output (binary/image/package)

Automation — Replace manual work with code

Orchestration — Coordinated automation across systems

Provisioning — Setting up infrastructure resources

Configuration Drift — Divergence from desired config

Infrastructure as Code (IaC) — Infra managed through code

Declarative — Define what state should be

Imperative — Define how to reach a state

Mutable Infrastructure — Manually changeable servers

Immutable Infrastructure — Rebuilt, not modified

Self-healing System — Auto-recovers from failure

Cattle vs Pets — Treat servers as disposable, not unique

Fail Fast — Detect and fix issues early

Feedback Loop — Continuous learning & improvement

Blue-Green Deployment — Two environments, zero downtime

Canary Release — Gradual rollout to users

Rolling Update — Incremental deployment of updates

Feature Flag — Enable/disable features dynamically

Shadow Deployment — Deploy without user exposure

A/B Testing — Compare two versions in production

Drift Detection — Identify config mismatches

Postmortem — Root-cause analysis after incidents

MTTR — Mean Time To Recovery

MTBF — Mean Time Between Failures

SLA — Service Level Agreement

SLO — Service Level Objective

SLI — Service Level Indicator

Change Management — Structured approach to system updates

Incident Response — Process for handling outages

Root Cause Analysis (RCA) — Finding the underlying issue

Blameless Culture — Learning-focused, no blame for mistakes


🧠 DevOps Culture & Practices

Shift-Left — Move testing/security earlier

Continuous Feedback — Ongoing performance insight

Continuous Learning — Constant skill improvement

Transparency — Shared visibility into operations

Collaboration — Cross-functional teamwork

Value Stream Mapping — Visualize flow of value

DORA Metrics — Key delivery performance indicators

Lead Time — Time from commit to deploy

Deployment Frequency — How often code is shipped

Change Failure Rate — % of failed deployments

MTTR — Mean time to restore service

SRE — Site Reliability Engineering discipline

Error Budget — Allowed failure threshold

Toil — Manual repetitive work (to be automated)

ChatOps — Automating ops via chat tools

Runbook — Documented operational procedures

Playbook — Incident response instruction set

Retrospective — Meeting to review improvements

Trunk-Based Development — Short-lived branches workflow

GitOps — Ops via Git commits

Platform Engineering — Internal platform creation for Dev teams

Service Ownership — Teams responsible for their services


💾 Version Control (Git)

Git — Distributed version control system

Repository — Code storage location

Commit — Save code snapshot

Branch — Independent code line

Merge — Combine branches

Rebase — Replay commits on top of another base

Tag — Mark specific release version

Fork — Personal copy of a repo

Clone — Local copy of a repo

Pull — Fetch & merge remote changes

Push — Upload commits to remote

Stash — Save local work temporarily

Conflict — Merge overlap between branches

HEAD — Pointer to current commit

Origin — Default name for remote repo

Submodule — Nested Git repo inside another

Gitignore — Exclude files from version control

Detached HEAD — Working on commit directly

Cherry-pick — Apply specific commit elsewhere

🧱 Infrastructure as Code (IaC)

IaC — Managing infra declaratively via code

Terraform — Open-source IaC tool by HashiCorp

Packer — Automated machine image builder

Pulumi — IaC with real programming languages

State File — Stores deployed infra state

Plan — Preview infra changes before apply

Apply — Execute infra plan

Destroy — Tear down infra resources

Module — Reusable component block

Provider — Plugin to manage infrastructure APIs

Resource — Infrastructure object definition

Variable — Configurable input value

Output — Exposed result from configuration

Backend — State storage mechanism

Data Source — Read existing infra data

Lifecycle Rule — Define create/destroy behavior

Template File — Generate dynamic configs

Drift Detection — Detect actual vs desired infra

Idempotency — Same outcome on multiple runs

Policy as Code — Enforce rules in IaC (e.g., OPA)

⚙️ Configuration Management

Ansible — Agentless config automation tool

Playbook — YAML task list in Ansible

Inventory — Host list definition

Role — Grouped tasks and variables

Handler — Triggered task after change

Puppet — Declarative config tool (DSL-based)

Chef — Ruby-based config automation

SaltStack — Event-driven config platform

State File — Desired system state (Salt)

Manifest — Puppet config file

Module — Reusable automation component

Templating — Dynamic file generation

Idempotent Task — Repeatable without side effects

Desired State — Target configuration model

Push vs Pull — Config update delivery model

🐳 Containers & Orchestration

Container — Isolated app runtime environment

Image — Template for containers

Docker — Container platform and CLI

Dockerfile — Container build instructions

Volume — Persistent container storage

Bind Mount — Host directory mounted inside container

Container Registry — Stores and distributes images

Tag — Image version label

Layer — Incremental build step in image

Docker Compose — Multi-container definition file

Kubernetes — Container orchestration platform

Pod — Smallest deployable K8s unit

Node — Worker machine in cluster

Cluster — Collection of worker nodes

Deployment — Manage desired pod replicas

ReplicaSet — Maintain desired pod count

DaemonSet — Run one pod per node

StatefulSet — Manage stateful applications

Job — Run finite task

CronJob — Scheduled recurring job

Service — Stable network endpoint

Ingress — External access routing

ConfigMap — Non-secret config data

Secret — Encrypted config values

Namespace — Logical cluster segmentation

Helm — Kubernetes package manager

Chart — Packaged K8s application

Release — Deployed Helm chart version

kubectl — CLI for Kubernetes

Kubelet — Node agent process

etcd — Cluster key-value store

Control Plane — Manages cluster state

Taint — Restrict pod scheduling

Affinity — Control pod placement rules

NodeSelector — Simple pod scheduling filter

Kustomize — K8s customization tool

Pod Security Policy — Define security constraints


🚀 CI/CD

Continuous Integration — Merge/test code frequently

Continuous Delivery — Automated deploy to staging

Continuous Deployment — Auto-deploy to production

Pipeline — Automated build/test/deploy stages

Stage — Logical step in pipeline

Job — Unit of work in CI/CD

Runner — Agent executing pipeline tasks

Build Artifact — Output from build

Artifact Repository — Store build outputs

Environment — Target deployment stage

Approval Gate — Manual approval step

Rollback — Revert to previous version

Cache — Store reusable build data

Parallel Jobs — Run multiple tasks simultaneously

Matrix Build — Test across environments

Webhook — Trigger pipeline on event

YAML Pipeline — Config file for CI/CD

Self-hosted Runner — Locally hosted pipeline executor

Ephemeral Runner — Short-lived build agent

Pipeline as Code — Pipeline defined in code repo

Dry Run — Test pipeline without execution

Build Trigger — Event that starts a pipeline

Post-build Action — Step after successful build

🔒 DevSecOps & Security

DevSecOps — Embed security in DevOps lifecycle

Vulnerability — Software security weakness

Threat — Potential exploit source

Exploit — Attack using vulnerability

CVE — Common Vulnerabilities and Exposures

CVSS — Vulnerability severity scoring system

Patch — Software fix for vulnerability

Compliance — Adhering to security standards

Audit Trail — Record of all changes

RBAC — Role-based access control

IAM — Identity and Access Management

Secret Management — Secure credential handling

Vault — Secret storage tool by HashiCorp

Encryption — Convert data to secure form

TLS/SSL — Secure communication protocols

OWASP — Web app security best practices

Static Analysis (SAST) — Scan code for issues

Dynamic Analysis (DAST) — Test running app

Dependency Scanning — Check libraries for flaws

Container Scanning — Inspect images for vulnerabilities

Image Signing — Verify container integrity

Zero Trust — Assume no implicit trust

Security Policy — Defined protection rules

Penetration Test — Ethical hacking simulation

SOC 2 — Security compliance standard

GDPR — Data privacy regulation


🔍 Monitoring, Logging & Observability

Observability — Measure internal system health

Monitoring — Watch system metrics

Alerting — Notify on metric thresholds

Metrics — Numeric performance indicators

Logs — Event and system messages

Traces — Request flow tracking

Prometheus — Metrics collection system

Grafana — Visualization dashboard tool

Loki — Log aggregation for Grafana

Elastic Stack — Search & log analytics suite

Fluentd — Log collector and forwarder

Fluent Bit — Lightweight log processor

Jaeger — Distributed tracing system

OpenTelemetry — Standard observability API

Alertmanager — Prometheus alert routing

Exporter — Prometheus data collector

Histogram — Metric distribution data

Cardinality — Number of metric label combinations

Blackbox Exporter — External endpoint testing

SLO — Service reliability target

SLI — Quantitative service indicator

Error Budget — Acceptable downtime window

Synthetic Monitoring — Simulated user testing

Health Check — Endpoint status check

Uptime — System availability metric


🧮 Metrics, Performance & Reliability

APM — Application Performance Monitoring

Latency — Response delay time

Throughput — Requests handled per second

Error Rate — Failed requests percentage

CPU Usage — Processor consumption level

Memory Leak — Unreleased memory over time

Disk I/O — Storage operation performance

Load Average — System CPU pressure indicator

Jitter — Variability in latency

Packet Loss — Missing data packets

Saturation — Resource utilization limit

Capacity Planning — Estimate needed resources

Bottleneck — Limiting performance factor

Rate Limiting — Control request rate

Retry Policy — Re-attempt on failure

Circuit Breaker — Stop repeated failing calls

Throttling — Intentionally slowing requests



🧰 Automation & Scripting

Bash — Unix shell scripting language

Python — Automation scripting language

PowerShell — Windows automation shell

Makefile — Define automation targets

Cron — Scheduler for periodic jobs

Webhook — Event-triggered HTTP callback

API — Programmatic interface

SDK — Developer toolkit

CLI — Command-line interface

Regex — Pattern matching syntax

YAML — Human-readable config format

JSON — Lightweight data format

JQ — JSON query processor

Curl — Command-line HTTP tool

SSH — Secure shell remote access

rsync — File sync utility

scp — Secure file copy

tmux — Terminal multiplexer

Expect — Automate interactive commands


🌐 Networking & System Operations

DNS — Domain Name System

HTTP — Web communication protocol

HTTPS — Secure HTTP

Load Balancer — Distributes traffic evenly

Reverse Proxy — Routes requests to backends

Nginx — Web server & proxy tool

Apache — Web server software

Firewall — Controls inbound/outbound traffic

Port — Communication endpoint identifier

TCP — Reliable connection protocol

UDP — Fast connectionless protocol

IP Address — Network identifier

CIDR — IP range notation

Subnet — Divided network segment

Routing Table — Packet direction rules

VPN — Virtual private network

NAT — Network Address Translation

Latency — Communication delay

Throughput — Network data rate

Traceroute — Trace packet route

Ping — Test connectivity

QoS — Quality of Service configuration






⚙️ DevOps Advanced Terminology Extension (100+ Additional Concepts)
🧩 Platform Engineering & GitOps

Internal Developer Platform — Self-service infra system

Golden Path — Standardized developer workflow

Golden Image — Pre-configured base system image

Platform as a Product — Treat platform like user-facing product

Backstage — Developer portal for internal platforms

GitOps — Infra/state managed through Git

Pull-based Deployment — Deploy triggered by Git commits

Drift Reconciliation — Auto-correct config drift

FluxCD — GitOps automation tool

Argo Rollouts — Progressive delivery controller

Kubernetes Operator — Automates app lifecycle management

Controller — Reconciles desired vs actual state

CRD — Custom Resource Definition

OPA — Open Policy Agent for policy enforcement

Rego — Policy language used by OPA

Crossplane — Manage infra via Kubernetes CRDs

KubeVela — Application delivery abstraction on K8s

Tanzu — VMware Kubernetes platform

Service Catalog — Internal list of provisionable services

Platform API — Interface for consuming internal services

🕸️ Service Mesh & Advanced Networking

Service Mesh — Layer for service-to-service communication

Istio — Popular service mesh for K8s

Linkerd — Lightweight service mesh alternative

Envoy — High-performance proxy used by service meshes

Sidecar Proxy — Co-located network proxy with app pod

Control Plane — Central config manager of service mesh

Data Plane — Actual traffic handling component

mTLS — Mutual TLS authentication

Ingress Gateway — External traffic entry point

Egress Gateway — External traffic exit point

Circuit Breaking — Stop cascading failures

Rate Limiting — Restrict request flow

Retry Policy — Re-attempt failed requests

Timeout Policy — Limit waiting time per request

Traffic Shadowing — Copy live traffic for testing

Traffic Splitting — Send percentage of traffic to version

Canary Analysis — Measure new version performance

Load Shedding — Drop low-priority requests

Service Discovery — Auto-detect service endpoints



🧠 Observability & Advanced Monitoring

White-box Monitoring — Internal metrics-based monitoring

Black-box Monitoring — External endpoint testing

Synthetic Transactions — Simulated user actions

High Cardinality — Many unique metric labels

Low Cardinality — Limited label combinations

Histogram — Distribution of observed values

Tracing Span — Individual operation trace unit

Trace Context — Metadata linking spans

Sampling Rate — % of traces collected

BPF / eBPF — Kernel-level event tracing technology

Metrics Scraping — Pull-based metric collection

Pushgateway — Push metrics to Prometheus

Alert Fatigue — Too many alerts cause desensitization

Anomaly Detection — Identify unusual metric behavior

Baseline — Normal expected metric value

Runbook Automation — Auto-response to alert

SLO Burn Rate — Speed of SLO violation

Error Budget Policy — Rules for error budget handling

Telemetry — System-generated monitoring data

SLI Calculation — Formula for service indicator



🔐 Policy, Compliance & Governance

Policy as Code — Manage policies programmatically

Governance — Control framework for compliance

Drift Detection — Monitor divergence from standards

FinOps — Financial management for cloud usage

Cost Allocation — Map expenses to teams/projects

Budget Alerting — Notify on cost thresholds

Tagging Policy — Standardize resource labels

Security Baseline — Minimal required protection setup

CIS Benchmark — Security configuration standard

NIST Framework — Security & compliance guidelines

ISO 27001 — Information security certification standard

SOC 2 Type II — Security audit report type

Data Retention Policy — Rules for storing data

Access Review — Regular user privilege audit

Least Privilege — Minimal required access principle

Separation of Duties — Divide responsibilities to reduce risk

Immutable Logs — Logs that cannot be altered

Audit Automation — Automated compliance verification

Data Masking — Hide sensitive data in non-prod

Security Hardening — Strengthen system configurations


🚀 Delivery Optimization & Resilience

Progressive Delivery — Controlled rollout strategy

Shadow Traffic — Mirror real traffic for test

Dark Launch — Deploy feature without exposure

Rollback Window — Time frame for rollback decision

Observability-driven Deployment — Data-based rollout

Deployment Freeze — Temporary stop for releases

Hotfix — Urgent bug fix release

Release Train — Scheduled batch releases

Pipeline Parallelization — Running pipeline tasks concurrently

Build Caching — Reuse previously built layers

Immutable Build — Non-reproducible build prevention

Artifact Promotion — Move artifact between environments

Change Approval Process — Review before deployment

Deployment Strategy — Defined rollout method

Release Governance — Rules for production pushes

A/B Testing — Compare new vs old version

Experimentation Platform — Manage controlled experiments

Blue-Green Rollback — Switch back to old environment

Resilience Testing — Evaluate fault tolerance

GameDay Exercise — Simulate production failures

Error Injection — Deliberately introduce faults

Circuit Breaker Pattern — Prevent cascading system failure

Bulkhead Pattern — Isolate system components

Retry Storm — Overload caused by mass retries

Timeout Budget — Combined timeout policy across services

🧮 Performance, Scaling & Systems

Autoscaling — Adjust resources automatically

HPA — Horizontal Pod Autoscaler in K8s

VPA — Vertical Pod Autoscaler

Cluster Autoscaler — Adjust node count dynamically

Resource Quota — Limit CPU/memory usage per namespace

Limit Range — Default resource limits in K8s

Throttling — Limit excessive usage

QoS Class — Pod priority classification

CGroup — Linux resource management control

Namespace Isolation — Logical resource separation

Node Affinity — Schedule pods on specific nodes

Pod Disruption Budget — Control voluntary disruptions

Availability Zone — Independent fault domain

Multi-tenancy — Share infra among teams securely

Resiliency — Ability to recover from faults

Fault Injection — Simulate component failure

Load Test — Measure performance under stress

Spike Test — Sudden traffic surge test

Chaos Monkey — Random failure injector

Latency Budget — Allowed delay threshold

Service Degradation — Reduced performance without failure


🧰 Tooling & Supporting Ecosystem

K9s — Kubernetes terminal UI

Lens — K8s IDE for cluster management

Tilt — Tool for local Kubernetes development

Skaffold — Automates local CI/CD for K8s

Kind — Kubernetes in Docker

Minikube — Local Kubernetes cluster

Vagrant — Virtual machine environment manager

Consul — Service discovery & key-value store

Nomad — HashiCorp workload orchestrator

Vault — Secret management platform

Velero — Backup & restore for Kubernetes

KEDA — Event-driven autoscaler for K8s

Kyverno — Kubernetes-native policy engine

Falco — Runtime security for containers

Trivy — Vulnerability scanner for containers

Grype — Image vulnerability scanning tool

Terrascan — IaC security scanning tool

Conftest — Policy testing for configuration files

Checkov — IaC security compliance scanner

Hadolint — Dockerfile linter

ShellCheck — Shell script static analyzer

Yamllint — YAML syntax checker
