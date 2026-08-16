# Converge [being built]

**Automated deployment and operations for customer environments.**

Converge helps provision, deploy, verify, monitor, and recover application environments across cloud providers.

### What it does

* Multi-cloud environment provisioning
* Pre-deployment validation
* Versioned deployments and rollbacks
* Health checks and deployment verification
* Observability and failure diagnosis
* Automated recovery
* Customer environment agent

### Architecture

```text
Customer
   ↓
Converge
   ├── Provision
   ├── Deploy
   ├── Verify
   ├── Observe
   └── Recover
        ↓
   ┌────┼────┐
  AWS  GCP  Azure
```

### Goal

Turn customer-specific deployments from manual engineering work into a **repeatable, observable, and self-recovering process**.

> Define the desired state. Converge the environment toward it.
