# Azure Disaster Recovery (DR) Setup Project

A project demonstrating Azure Backup and Site Recovery (ASR) for cross-region VM replication.

## 📋 Overview
- Configured Azure Backup for a VM in East US.
- Replicated the VM to West US using Azure Site Recovery.
- Tested failover and validated recovery workflows.

## 🛠️ Prerequisites
- Azure account
- Virtual Machine in Azure
- Azure Backup & Site Recovery permissions

## 📂 Repository Structure
Explain the purpose of each folder/file.

## 🚀 Step-by-Step Setup
### 1. Azure Backup Configuration
- Created a Recovery Services Vault.
- Linked VM to a daily backup policy.
- Triggered manual backups.

### 2. Azure Site Recovery Replication
- Enabled cross-region replication (East US → West US).
- Configured RPO/RTO settings.

### 3. Failover Testing
- Performed test failover to West US.
- Validated VM functionality post-recovery.

## 📸 Screenshots
![screenshots]


## 📊 Architecture Diagram
![architecture-diagram]

## 📝 Lessons Learned
- Importance of RPO/RTO alignment with business needs.
- Monitoring backup/replication jobs for reliability.

## 🔗 Resources
- [Azure Backup Docs](https://learn.microsoft.com/en-us/azure/backup/)
- [Azure Site Recovery Tutorial](https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-tutorial-enable-replication)
