
# Kubernetes YAML Manifests and Prompts

This repository contains Kubernetes YAML manifests generated using the `kubectl-ai` plugin. Each manifest was created using a specific prompt to illustrate various Kubernetes features.

| NAME                  | PROMPT                                                                                         | DESCRIPTION                                              | EXAMPLE                                          |
|-----------------------|------------------------------------------------------------------------------------------------|----------------------------------------------------------|--------------------------------------------------|
| app.yaml              | Generate a Kubernetes deployment manifest for a simple web application with an Nginx container. | Basic deployment manifest for an Nginx web application.  | [app.yaml](yaml/app.yaml)                        |
| app-livenessProbe.yaml| Generate a Kubernetes deployment manifest with livenessProbe for an Nginx container.           | Deployment manifest with livenessProbe.                  | [app-livenessProbe.yaml](yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml| Generate a Kubernetes deployment manifest with readinessProbe for an Nginx container.          | Deployment manifest with readinessProbe.                 | [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | Generate a Kubernetes deployment manifest with volume mounts for an Nginx container.           | Deployment manifest with volume mounts.                  | [app-volumeMounts.yaml](yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml      | Generate a Kubernetes CronJob manifest for a simple scheduled task.                            | CronJob manifest for a scheduled task.                   | [app-cronjob.yaml](yaml/app-cronjob.yaml)        |
| app-job.yaml          | Generate a Kubernetes Job manifest for a one-time task.                                        | Job manifest for a one-time task.                        | [app-job.yaml](yaml/app-job.yaml)                |
| app-multicontainer.yaml| Generate a Kubernetes deployment manifest with multiple containers in a single pod.           | Deployment manifest with multiple containers.            | [app-multicontainer.yaml](yaml/app-multicontainer.yaml) |
| app-resources.yaml    | Generate a Kubernetes deployment manifest with resource limits and requests for an Nginx container. | Deployment manifest with resource limits and requests. | [app-resources.yaml](yaml/app-resources.yaml)    |
| app-secret-env.yaml   | Generate a Kubernetes deployment manifest with environment variables from a secret for an Nginx container. | Deployment manifest with environment variables from a secret. | [app-secret-env.yaml](yaml/app-secret-env.yaml) |

## References
- [kubectl-ai GitHub Repository](https://github.com/sozercan/kubectl-ai)