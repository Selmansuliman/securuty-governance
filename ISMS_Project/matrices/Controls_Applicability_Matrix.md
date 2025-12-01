# Controls Applicability Matrix

Control | Applicability | Implementation Notes | Evidence
---|---|---|---
A.8.2 (Identity Mgmt) | Applicable | Use centralized IAM (Okta/AzureAD) | IAM configuration exports
A.8.13 (Backup) | Applicable | Daily incrementals, weekly full | Backup job logs
A.8.24 (Cryptography) | Applicable | Use HSM/KMS for key storage | KMS policy, key inventory
