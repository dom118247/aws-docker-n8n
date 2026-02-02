# N8N CloudFormation Deployment

CloudFormation template that creates an EC2 instance hosting two Docker containers:

- Traefik: Reverse proxy with automatic HTTPS/SSL
- N8N: Workflow automation platform

When deployed, Traefik automatically routes traffic from your domain (e.g., `n8n.dom-beard.com`) to the N8N application with automatic SSL certificate management.
