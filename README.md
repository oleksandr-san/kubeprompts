# kubeprompts
A collection of AI propts for Kubernetes administration

## Prompts

| Name | Prompt | Description | Example |
| --- | --- | --- | --- |
| app.yaml | Create a deployment | Create a deployment with a single container | [app.yaml](./yaml/app.yaml) |
| app-livenessProbe.yaml | Add a liveness probe | Add a liveness probe to a deployment | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | Add a readiness probe | Add a readiness probe to a deployment | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | Add a volume mount | Add a volume mount to a deployment | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml | Create a cronjob | Create a cronjob | [app-cronjob.yaml](./yaml/app-cronjob.yaml) |
| app-job.yaml | Create a job | Create a job | [app-job.yaml](./yaml/app-job.yaml) |
| app-multicontainer.yaml | Create a deployment with multiple containers | Create a deployment with multiple containers | [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources.yaml | Add resource limits | Add resource limits to a deployment | [app-resources.yaml](./yaml/app-resources.yaml) |
| app-secret-env.yaml | Add a secret as an environment variable | Add a secret as an environment variable to a deployment | [app-secret-env.yaml](./yaml/app-secret-env.yaml) |