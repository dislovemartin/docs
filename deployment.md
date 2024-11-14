## Deployment Guide

### Prerequisites

- Docker v20.10+
- Kubernetes v1.24+
- Helm v3.8+

### Deployment Steps

1. **Configure Environment Variables:**
   ```bash
   cp .env.example .env
   # Edit .env with your values
   ```

2. **Deploy Infrastructure:**
   ```bash
   ./scripts/deployment/deploy_infrastructure.sh
   ```

3. **Deploy Applications:**
   ```bash
   ./scripts/deployment/deploy_applications.sh
   ```

4. **Verify Deployment:**
   ```bash
   ./scripts/deployment/verify_deployment.sh
   ```
