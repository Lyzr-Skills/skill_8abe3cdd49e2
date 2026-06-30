NAME:
Cloud & Container Security

PURPOSE:
Cloud and container security assessment across identity, network exposure, storage, and orchestration layers.

CAPABILITIES:
- IAM and identity/role analysis (privilege escalation paths, trust policies)
- Storage exposure review (S3, Blob, GCS) and public-access misconfiguration
- Kubernetes RBAC, pod security context, and namespace isolation analysis
- Container image and runtime security
- Cloud network exposure and metadata-service (SSRF) risk analysis
- Cloud logging/detection gap review

PLATFORMS:
AWS, Azure, GCP, Kubernetes

TOOLS:
- aws-cli, az-cli, gcloud, kubectl
- Trivy, kube-bench
- ScoutSuite / Prowler (reference)

WORKFLOW:
1. Identity and IAM analysis
2. Network exposure review
3. Storage and data inspection
4. Container / Kubernetes review
5. Logging and detection gap review
6. Risk interpretation and remediation

ENVIRONMENT DEFAULTS:
Misconfigured least-privilege is the most likely entry point; SSRF-to-metadata is high-priority; flag exact IAM/policy strings as needing target-environment validation.

REFERENCE FRAMEWORKS:
MITRE ATT&CK (Cloud), CIS Cloud Benchmarks, CVSS v3.1
