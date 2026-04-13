# Kubeflow Pipelines (Trimmed Manifests)

This repository contains a minimal subset of manifests from the Kubeflow Pipelines project, extracted for deployment purposes.
NOTE: Removed .\manifests\kustomize\third-party\minio\base\mlpipeline-minio-artifact-secret.yaml, so it must be created manually before deployment.

## Source

Original project:
https://github.com/kubeflow/pipelines

## License

This project includes code from Kubeflow Pipelines, which is licensed under the Apache License 2.0.

See the LICENSE and NOTICE files for details.

## Notes

- Only the required manifests are included (e.g. kustomize resources)
- This repository is intended for GitOps deployment (e.g. ArgoCD)
- It does not include the full upstream source code