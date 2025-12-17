# Applications

User-facing applications and services running on the cluster.

## Components

### Homer
Dashboard and homepage for accessing all services.
- Central hub for service navigation
- Access: https://homer0213.kro.kr

### Docusaurus
Documentation site for infrastructure and services.
- Built from infrastructure repository
- Access: https://docusaurus0213.kro.kr

### Code Server
Web-based VS Code IDE for remote development.
- Browser-based code editor
- Supports extensions and terminal access

### Umami
Privacy-focused web analytics platform.
- Self-hosted analytics solution
- No cookies or tracking

### Kubernetes Dashboard
Web UI for Kubernetes cluster management.
- Cluster resource visualization
- Workload monitoring and management

### Backup
Automated backup jobs for critical services.
- Gitea backup to MinIO
- Scheduled via CronJob

## Deployment

Managed by ArgoCD. All applications are deployed with automated sync and prune enabled.
