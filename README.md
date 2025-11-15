🔵 Docker (Expect 8–12 questions)

Image vs Container

Dockerfile instructions (COPY vs ADD, ENTRYPOINT vs CMD)

Multi-stage builds

Docker networking

Volumes & Bind Mounts

Difference between Docker Compose & Dockerfile

💡 MUST KNOW:
✔ How to reduce image size
✔ How to debug failing containers

🔵 Kubernetes (Expect 10–15 questions — MOST IMPORTANT)

You MUST understand:

Deployments (ReplicaSets, Rollouts, Rollbacks)

Services (ClusterIP, NodePort, LoadBalancer)

Ingress Controller

ConfigMaps vs Secrets

Liveness vs Readiness probe

HPA (Horizontal Pod Autoscaler)

Namespaces

Persistent Volume (PV/PVC)

Taints & Tolerations

Node Affinity

💡 PRIORITY:
Explain the workflow of:

“When you run kubectl apply -f deployment.yaml, what actually happens?”

This question appears in almost every Cognizant DevOps interview.

🔵 Terraform (Expect 6–10 questions)

What is Terraform state?

What is a backend?

Providers

Modules

terraform plan vs terraform apply

Lifecycle rules

Workspaces

Remote state locking

tfvars usage

Handling sensitive data

💡 MUST KNOW:
✔ “What happens if terraform state is deleted?”
✔ “How do you avoid configuration drift?”

🔵 Ansible (Expect 4–6 questions)

Inventory

Playbook vs Role

Handlers

Variables

Templates

idempotency

Conditionals

Ansible Vault

🔵 Azure DevOps (Expect 5 questions)

YAML vs Classic pipelines

Release pipeline

Stages, Jobs, Tasks

Hosted agents

Variable groups

Secrets mgmt

CI vs CD vs Continuous Deployment

Integration with Kubernetes

🔵 Shell Scripting (Expect 3–5 questions)

They ask small logical questions like:

Write a script to find files larger than 100MB

Script to read a file line by line

Script to monitor CPU usage

Script to restart a service if down

🔵 Linux (Expect 7–10 questions)

top, ps, netstat, ss, iostat, vmstat

CPU/Memory diagnostics

Permissions (chmod, chown, groups)

Process mgmt (kill, nice, renice)

Systemctl

Logs (/var/log)

Networking (ping, traceroute, curl)

Disk mgmt (df, du, mount)

🔥 3. Cognizant-Specific Interview Questions (Very Common)
Docker

How do you troubleshoot a container stuck in restart loop?

Difference between ENTRYPOINT and CMD?

How do you reduce image size?

How do you pass environment variables into containers?

Kubernetes

Explain Deployment → ReplicaSet → Pod workflow.

What happens during a rolling update?

Difference between Ingress vs LoadBalancer.

Explain liveness and readiness probe.

How does HPA work?

How do you debug a CrashLoopBackOff pod?

How to check logs of a container inside a pod?

Explain ConfigMap and Secret use cases.

How does kube-proxy work?

Explain etcd.

Terraform

What is Terraform state? Why is it important?

What is the purpose of backends?

What is the difference between resource vs module?

What are data sources?

How to handle secrets?

How do you run Terraform pipelines in CI/CD?

How do you version modules?

Ansible

How is idempotency achieved in Ansible?

Role structure

Ansible Vault usage

Tasks vs handlers

When would you use Jinja2 templates?

Azure DevOps

Explain the flow of a YAML pipeline.

How do you trigger pipelines automatically?

Multi-stage vs single-stage pipelines.

Using variable groups & secrets.

Deploying to Kubernetes using ADO.

Linux

CPU is high — how do you troubleshoot?

Disk is full — how do you find which folder?

Difference: load average vs CPU usage

What is a zombie process?

What does dmesg do?
