# Ansible Jenkins Deployment Automation

## Overview
This project automates application deployment using Ansible integrated with Jenkins for continuous delivery.

## Tech Stack
- Jenkins
- Ansible
- Apache Maven
- Apache Tomcat
- AWS EC2
- Git

## Architecture Workflow
1. Developer pushes code to Git repository.
2. Jenkins pulls the code and builds WAR file.
3. Jenkins triggers Ansible playbook.
4. Ansible connects to production server.
5. WAR file is deployed to Tomcat.
6. Tomcat service is restarted.

## Key Features
- Automated deployment using Ansible
- CI/CD integration with Jenkins
- Reduced manual intervention

## Challenges
- SSH key configuration
- Ansible connectivity issues
- Deployment troubleshooting

## Results
- Faster and reliable deployments
- Improved automation efficiency

## Documentation
Refer to `project-report.pdf`.
