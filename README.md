# end-to-end-ci-cd-pipeline-gcp
End-to-end CI/CD pipeline architecture on Google Cloud Platform (GCP) using Cloud Build, Docker, and Kubernetes (GKE).
# GCP CI/CD DevOps Pipeline

This project demonstrates an end-to-end CI/CD pipeline architecture on Google Cloud Platform (GCP).

## Tools & Services Used
- Google Cloud Build
- Google Container Registry (GCR)
- Google Kubernetes Engine (GKE)
- Docker
- GitHub

## CI/CD Workflow
1. Code pushed to GitHub repository
2. Cloud Build triggers automatically
3. Docker image is built
4. Image pushed to Google Container Registry
5. Application deployed to GKE cluster

## Architecture Overview
The pipeline follows cloud-native DevOps best practices for scalable and automated deployments on GCP.

## Use Case
This project is designed to showcase CI/CD concepts and GCP DevOps architecture.

## Author
Anjali Singh  
GitHub: https://github.com/singhanjali33375-rgb
gcp-ci-cd-devops-pipeline/
│
├── README.md
├── .gitignore
│
├── cloudbuild.yaml
│
├── docker/
│   └── Dockerfile
│
├── kubernetes/
│   ├── deployment.yaml
│   └── service.yaml
│
└── images/
    └── gcp-cicd-architecture.png
    🎤 PRESENTATION SLIDES
🔹 Slide 1 – Title
End-to-End CI/CD Pipeline on Google Cloud Platform
By: Anjali Singh
🔹 Slide 2 – Problem Statement
Manual deployments are time-consuming and error-prone.
A CI/CD pipeline is required to automate build, test, and deployment.
🔹 Slide 3 – Why GCP?
Fully managed DevOps services
Scalable & reliable
Native Kubernetes support
Faster CI/CD with Cloud Build
🔹 Slide 4 – Tools Used
GitHub
Google Cloud Build
Docker
Google Container Registry
Google Kubernetes Engine (GKE)
🔹 Slide 5 – CI/CD Workflow
Developer → GitHub → Cloud Build → Docker Image → GCR → GKE
🔹 Slide 6 – Architecture Diagram
🔹 Slide 7 – Benefits
Automated deployments
Faster release cycles
Scalable infrastructure
Reduced manual errors
🔹 Slide 8 – Use Cases
Microservices deployment
Cloud-native applications
DevOps automation
Slide 9 – Conclusion
This project demonstrates a cloud-native CI/CD pipeline design using GCP best practices.
• Designed an end-to-end CI/CD pipeline architecture on Google Cloud Platform (GCP).
• Used Cloud Build, Docker, and Kubernetes (GKE) for automated deployments.
• Demonstrated cloud-native DevOps best practices.
