# PowerShell Work Examples

This page highlights some real-world PowerShell work in large-scale enterprise environments.

---

## 🏗 Infrastructure

### WSUS
- Approved updates via script (selective by classification/product)
- Cleanup scripts across multi-tiered WSUS hierarchies (bottom-up)

### IIS
- Automated SSL cert binding and renewals
- Memory tuning and app pool management
- Applied CIS-CAT hardening via PowerShell

### SQL Server
- Scripted installs with pre-checks for HA/AlwaysOn
- Hardening and performance optimisation with PowerShell wrappers

### Active Directory
- Populated custom user attributes across 12k users for HR integration
- Joiner/leaver lifecycle automation

### VMWare
- Full VM provisioning (vNICs, ISOs, boot order, snapshots) via vSphere API
- Datastore cleanup and snapshot lifecycle scripts

### Citrix
- Global DDC inventory across regions
- Automated delivery group management and power controls

---

## 💻 Endpoint Management (ConfigMgr/SCCM)

### Core Config
- Full environment deployment into Azure via code
- Simplified in-place upgrade process

### Updates
- End-to-end software update automation from CSV input
- Reporting, targeting, deployment and rollback

### App Management
- Packaging, deployment, WMI querying for complex setups

### OS Deployment
- Task sequence automation (driver packs, WMI filters, step logic)
- CI/Baseline automation via code

---

## ☁ Azure

### VM & General
- Multi-tenant asset discovery (output to DB)
- Tagging remediation and daily lifecycle automation

### Key Vault
- Network lockdown and secure secret handling

### Storage
- Scripted upload/unlock of files, container provisioning

### Backup & DR
- Automated backup policy creation
- Snapshot + restore orchestration
- DR testing workflows

### Image Gallery
- Full automation of gallery + versioning

### Cost Management
- VM/disk rightsizing via script
- Analysis using built-in PowerShell module

### Azure Policy
- Policy/initiative deployment across tenants
- Custom definition scripting

---

## 🔐 Security

### Vulnerability Management
- OS hardening (GPO/PowerShell)
- CVE remediation at scale (ACLs, services, reg edits)
- Scan parsing and deduplication

### Patching
- Automated complex patch cycles
- Large-scale failure identification

---

## 🧠 Process & Quality

### Change Management
- CHG ticket templates + scheduling tooling

### Data Gathering
- Cross-platform data ingestion into SQL (AD, Citrix, VMWare, Workday)
