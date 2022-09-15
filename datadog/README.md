# Datadog
Datadog is installed using the datadog helm chart to the EKS cluster. For this to work, there is also an ExternalSecret object created to pull the datadog app and api keys from AWS Secrets manager utilizing the external secrets operator.

Application set for this addon
- [argocd-repos.yaml](../../application-sets/datadog.yaml)

### Useful links
- [Datadog EKS Documentation](https://www.datadoghq.com/blog/eks-monitoring-datadog/)
- [Datadog EKS Fargate Documentation](https://docs.datadoghq.com/integrations/eks_fargate/)