# trivy-tekton-pipeline

This repository contains a task that uses [trivy](https://github.com/aquasecurity/trivy) tool for detecting vulnerabilities present in an container image. With this task we can scan a registry which contains an image for vulnerabilities.

# Installing the task
kubectl apply -f https://raw.githubusercontent.com/mbharatk/trivy-tekton-pipeline/main/task/img-scan-task.yaml
