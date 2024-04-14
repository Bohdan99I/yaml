# Prompt Engineering Portfolio

Welcome to my Prompt Engineering Portfolio! Below is a table showcasing prompts for various Kubernetes manifests along with their descriptions and examples.

## Prompts and Descriptions

| NAME                    | PROMPT                                                                                                | DESCRIPTION                                                 | EXAMPLE                                                   |
| ----------------------- | ----------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | --------------------------------------------------------- |
| app.yaml                | Create a Pod manifest that defines a single-container Pod running the application.                    | This prompt generates a basic Pod manifest.                 | [app.yaml](./yaml/app.yaml)                               |
| app-livenessProbe.yaml  | Create a Pod manifest with a Liveness Probe to ensure the application is responsive.                  | This prompt adds a Liveness Probe to the Pod.               | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml)   |
| app-readinessProbe.yaml | Create a Pod manifest with a Readiness Probe to ensure the application is ready to serve traffic.     | This prompt adds a Readiness Probe to the Pod.              | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml   | Create a Pod manifest with Volume Mounts to persist data within the container.                        | This prompt demonstrates the usage of Volume Mounts.        | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml)     |
| app-cronjob.yaml        | Create a CronJob manifest that schedules a job to run periodically.                                   | This prompt creates a CronJob for scheduled tasks.          | [app-cronjob.yaml](./yaml/app-cronjob.yaml)               |
| app-job.yaml            | Create a Job manifest to run a one-off task in the cluster.                                           | This prompt defines a Job for executing tasks.              | [app-job.yaml](./yaml/app-job.yaml)                       |
| app-multicontainer.yaml | Create a Pod manifest with multiple containers, each serving a different purpose.                     | This prompt demonstrates the usage of multi-container Pods. | [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources.yaml      | Create a Pod manifest that specifies resource requests and limits for CPU and memory.                 | This prompt defines resource requirements for the Pod.      | [app-resources.yaml](./yaml/app-resources.yaml)           |
| app-secret-env.yaml     | Create a Pod manifest that injects sensitive information stored in a Secret as environment variables. | This prompt illustrates using Secrets in Pod environments.  | [app-secret-env.yaml](./yaml/app-secret-env.yaml)         |
