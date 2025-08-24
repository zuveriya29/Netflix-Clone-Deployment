DevSecOps Project – Netflix Clone Deployment

Hello All, this project is a fully automated, secure, and monitored Netflix clone web application deployed on Kubernetes with DevSecOps practices.

Tools & Technologies Used:

AWS EC2 – Cloud infrastructure
Docker & Docker Hub – Containerization & image registry
SonarQube, Trivy – Security scanning
Jenkins – CI/CD pipeline automation
Kubernetes + Helm – Container orchestration
Prometheus & Grafana – Monitoring & alerting
ArgoCD – GitOps-based deployment

Project Workflow :
Application containerized using Docker and deployed on an EC2 instance.Applied SonarQube for code quality analysis.
Used Trivy/Kube-bench for container and Kubernetes security scanning.Configured a Jenkins pipeline for continuous integration and deployment.
Built Docker images and pushed them to Docker Hub.Deployed the Netflix clone app to a Kubernetes cluster using Helm charts for scalability and easy management.Integrated Prometheus and Grafana for monitoring metrics and visualizing dashboards.
And finally used ArgoCD for continuous delivery, syncing Kubernetes manifests from GitHub to the cluster automatically.
